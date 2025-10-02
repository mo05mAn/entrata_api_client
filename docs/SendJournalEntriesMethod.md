# SendJournalEntriesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendJournalEntriesMethodParams**](SendJournalEntriesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_journal_entries_method import SendJournalEntriesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendJournalEntriesMethod from a JSON string
send_journal_entries_method_instance = SendJournalEntriesMethod.from_json(json)
# print the JSON string representation of the object
print(SendJournalEntriesMethod.to_json())

# convert the object into a dict
send_journal_entries_method_dict = send_journal_entries_method_instance.to_dict()
# create an instance of SendJournalEntriesMethod from a dict
send_journal_entries_method_from_dict = SendJournalEntriesMethod.from_dict(send_journal_entries_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


