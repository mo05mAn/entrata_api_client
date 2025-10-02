# GetAccessibleClientsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The ID of the request | 
**code** | **int** | The status code of the response | 
**result** | [**GetAccessibleClientsSuccessResponseResult**](GetAccessibleClientsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_accessible_clients_success_response import GetAccessibleClientsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessibleClientsSuccessResponse from a JSON string
get_accessible_clients_success_response_instance = GetAccessibleClientsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetAccessibleClientsSuccessResponse.to_json())

# convert the object into a dict
get_accessible_clients_success_response_dict = get_accessible_clients_success_response_instance.to_dict()
# create an instance of GetAccessibleClientsSuccessResponse from a dict
get_accessible_clients_success_response_from_dict = GetAccessibleClientsSuccessResponse.from_dict(get_accessible_clients_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


