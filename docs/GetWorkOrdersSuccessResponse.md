# GetWorkOrdersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Identifier of the request | 
**result** | [**GetWorkOrdersSuccessResponseResult**](GetWorkOrdersSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_work_orders_success_response import GetWorkOrdersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersSuccessResponse from a JSON string
get_work_orders_success_response_instance = GetWorkOrdersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersSuccessResponse.to_json())

# convert the object into a dict
get_work_orders_success_response_dict = get_work_orders_success_response_instance.to_dict()
# create an instance of GetWorkOrdersSuccessResponse from a dict
get_work_orders_success_response_from_dict = GetWorkOrdersSuccessResponse.from_dict(get_work_orders_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


