# GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**labor** | [**List[GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner]**](GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner.md) |  | [optional] 
**sub_total** | [**GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsSubTotal**](GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsSubTotal.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_work_orders_success_response_result_work_orders_work_order_inner_labors import GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors from a JSON string
get_work_orders_success_response_result_work_orders_work_order_inner_labors_instance = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors.to_json())

# convert the object into a dict
get_work_orders_success_response_result_work_orders_work_order_inner_labors_dict = get_work_orders_success_response_result_work_orders_work_order_inner_labors_instance.to_dict()
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors from a dict
get_work_orders_success_response_result_work_orders_work_order_inner_labors_from_dict = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors.from_dict(get_work_orders_success_response_result_work_orders_work_order_inner_labors_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


