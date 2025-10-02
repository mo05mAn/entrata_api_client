# GetWorkOrdersSuccessResponseResultWorkOrders


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**work_order** | [**List[GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner]**](GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_work_orders_success_response_result_work_orders import GetWorkOrdersSuccessResponseResultWorkOrders

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrders from a JSON string
get_work_orders_success_response_result_work_orders_instance = GetWorkOrdersSuccessResponseResultWorkOrders.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersSuccessResponseResultWorkOrders.to_json())

# convert the object into a dict
get_work_orders_success_response_result_work_orders_dict = get_work_orders_success_response_result_work_orders_instance.to_dict()
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrders from a dict
get_work_orders_success_response_result_work_orders_from_dict = GetWorkOrdersSuccessResponseResultWorkOrders.from_dict(get_work_orders_success_response_result_work_orders_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


