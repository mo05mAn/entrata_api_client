# SendJournalEntriesSuccessResponseResultGlHeadersGlHeaderInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | The node identifier for the GL header insertion. | 
**status** | **str** | The status of the GL header insertion. | 
**message** | **str** | Message indicating the result of the GL header insertion. | 
**gl_header_id** | **str** | The unique identifier for the GL header. | 
**je_number** | **str** | The journal entry number. | 

## Example

```python
from openapi_client.models.send_journal_entries_success_response_result_gl_headers_gl_header_inner import SendJournalEntriesSuccessResponseResultGlHeadersGlHeaderInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendJournalEntriesSuccessResponseResultGlHeadersGlHeaderInner from a JSON string
send_journal_entries_success_response_result_gl_headers_gl_header_inner_instance = SendJournalEntriesSuccessResponseResultGlHeadersGlHeaderInner.from_json(json)
# print the JSON string representation of the object
print(SendJournalEntriesSuccessResponseResultGlHeadersGlHeaderInner.to_json())

# convert the object into a dict
send_journal_entries_success_response_result_gl_headers_gl_header_inner_dict = send_journal_entries_success_response_result_gl_headers_gl_header_inner_instance.to_dict()
# create an instance of SendJournalEntriesSuccessResponseResultGlHeadersGlHeaderInner from a dict
send_journal_entries_success_response_result_gl_headers_gl_header_inner_from_dict = SendJournalEntriesSuccessResponseResultGlHeadersGlHeaderInner.from_dict(send_journal_entries_success_response_result_gl_headers_gl_header_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


