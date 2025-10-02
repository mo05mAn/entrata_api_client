# GetLeaseDocumentsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | Status code of the response. | 
**result** | [**GetLeaseDocumentsSuccessResponseResult**](GetLeaseDocumentsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_lease_documents_success_response import GetLeaseDocumentsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsSuccessResponse from a JSON string
get_lease_documents_success_response_instance = GetLeaseDocumentsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsSuccessResponse.to_json())

# convert the object into a dict
get_lease_documents_success_response_dict = get_lease_documents_success_response_instance.to_dict()
# create an instance of GetLeaseDocumentsSuccessResponse from a dict
get_lease_documents_success_response_from_dict = GetLeaseDocumentsSuccessResponse.from_dict(get_lease_documents_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


