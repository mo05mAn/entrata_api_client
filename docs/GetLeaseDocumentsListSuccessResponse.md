# GetLeaseDocumentsListSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | Status code of the response. | 
**result** | [**GetLeaseDocumentsListSuccessResponseResult**](GetLeaseDocumentsListSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_documents_list_success_response import GetLeaseDocumentsListSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsListSuccessResponse from a JSON string
get_lease_documents_list_success_response_instance = GetLeaseDocumentsListSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsListSuccessResponse.to_json())

# convert the object into a dict
get_lease_documents_list_success_response_dict = get_lease_documents_list_success_response_instance.to_dict()
# create an instance of GetLeaseDocumentsListSuccessResponse from a dict
get_lease_documents_list_success_response_from_dict = GetLeaseDocumentsListSuccessResponse.from_dict(get_lease_documents_list_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


