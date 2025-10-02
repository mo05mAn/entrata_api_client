# SendLeaseDocumentsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**SendLeaseDocumentsSuccessResponseResult**](SendLeaseDocumentsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_lease_documents_success_response import SendLeaseDocumentsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseDocumentsSuccessResponse from a JSON string
send_lease_documents_success_response_instance = SendLeaseDocumentsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendLeaseDocumentsSuccessResponse.to_json())

# convert the object into a dict
send_lease_documents_success_response_dict = send_lease_documents_success_response_instance.to_dict()
# create an instance of SendLeaseDocumentsSuccessResponse from a dict
send_lease_documents_success_response_from_dict = SendLeaseDocumentsSuccessResponse.from_dict(send_lease_documents_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


