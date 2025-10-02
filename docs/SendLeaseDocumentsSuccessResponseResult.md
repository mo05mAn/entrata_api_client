# SendLeaseDocumentsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**files** | [**SendLeaseDocumentsSuccessResponseResultFiles**](SendLeaseDocumentsSuccessResponseResultFiles.md) |  | 

## Example

```python
from entrata_api_client.models.send_lease_documents_success_response_result import SendLeaseDocumentsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseDocumentsSuccessResponseResult from a JSON string
send_lease_documents_success_response_result_instance = SendLeaseDocumentsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendLeaseDocumentsSuccessResponseResult.to_json())

# convert the object into a dict
send_lease_documents_success_response_result_dict = send_lease_documents_success_response_result_instance.to_dict()
# create an instance of SendLeaseDocumentsSuccessResponseResult from a dict
send_lease_documents_success_response_result_from_dict = SendLeaseDocumentsSuccessResponseResult.from_dict(send_lease_documents_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


