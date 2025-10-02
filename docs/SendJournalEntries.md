# SendJournalEntries


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendJournalEntriesMethod**](SendJournalEntriesMethod.md) |  | 

## Example

```python
from openapi_client.models.send_journal_entries import SendJournalEntries

# TODO update the JSON string below
json = "{}"
# create an instance of SendJournalEntries from a JSON string
send_journal_entries_instance = SendJournalEntries.from_json(json)
# print the JSON string representation of the object
print(SendJournalEntries.to_json())

# convert the object into a dict
send_journal_entries_dict = send_journal_entries_instance.to_dict()
# create an instance of SendJournalEntries from a dict
send_journal_entries_from_dict = SendJournalEntries.from_dict(send_journal_entries_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


