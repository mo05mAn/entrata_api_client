# GetWorkOrdersSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**work_orders** | [**GetWorkOrdersSuccessResponseResultWorkOrders**](GetWorkOrdersSuccessResponseResultWorkOrders.md) |  | 

## Example

```python
from openapi_client.models.get_work_orders_success_response_result import GetWorkOrdersSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersSuccessResponseResult from a JSON string
get_work_orders_success_response_result_instance = GetWorkOrdersSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersSuccessResponseResult.to_json())

# convert the object into a dict
get_work_orders_success_response_result_dict = get_work_orders_success_response_result_instance.to_dict()
# create an instance of GetWorkOrdersSuccessResponseResult from a dict
get_work_orders_success_response_result_from_dict = GetWorkOrdersSuccessResponseResult.from_dict(get_work_orders_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


