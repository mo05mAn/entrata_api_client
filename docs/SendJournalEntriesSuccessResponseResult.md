# SendJournalEntriesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_headers** | [**SendJournalEntriesSuccessResponseResultGlHeaders**](SendJournalEntriesSuccessResponseResultGlHeaders.md) |  | 

## Example

```python
from openapi_client.models.send_journal_entries_success_response_result import SendJournalEntriesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendJournalEntriesSuccessResponseResult from a JSON string
send_journal_entries_success_response_result_instance = SendJournalEntriesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendJournalEntriesSuccessResponseResult.to_json())

# convert the object into a dict
send_journal_entries_success_response_result_dict = send_journal_entries_success_response_result_instance.to_dict()
# create an instance of SendJournalEntriesSuccessResponseResult from a dict
send_journal_entries_success_response_result_from_dict = SendJournalEntriesSuccessResponseResult.from_dict(send_journal_entries_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


