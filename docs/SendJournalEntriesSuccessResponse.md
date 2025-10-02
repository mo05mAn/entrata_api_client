# SendJournalEntriesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**SendJournalEntriesSuccessResponseResult**](SendJournalEntriesSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_journal_entries_success_response import SendJournalEntriesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendJournalEntriesSuccessResponse from a JSON string
send_journal_entries_success_response_instance = SendJournalEntriesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendJournalEntriesSuccessResponse.to_json())

# convert the object into a dict
send_journal_entries_success_response_dict = send_journal_entries_success_response_instance.to_dict()
# create an instance of SendJournalEntriesSuccessResponse from a dict
send_journal_entries_success_response_from_dict = SendJournalEntriesSuccessResponse.from_dict(send_journal_entries_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


