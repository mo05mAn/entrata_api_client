# GetAccessibleServicesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The ID of the request | 
**code** | **int** | The status code of the response | 
**result** | [**GetAccessibleServicesSuccessResponseResult**](GetAccessibleServicesSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_accessible_services_success_response import GetAccessibleServicesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessibleServicesSuccessResponse from a JSON string
get_accessible_services_success_response_instance = GetAccessibleServicesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetAccessibleServicesSuccessResponse.to_json())

# convert the object into a dict
get_accessible_services_success_response_dict = get_accessible_services_success_response_instance.to_dict()
# create an instance of GetAccessibleServicesSuccessResponse from a dict
get_accessible_services_success_response_from_dict = GetAccessibleServicesSuccessResponse.from_dict(get_accessible_services_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


