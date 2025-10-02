# GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrdersChildWorkOrderInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**maintenance_request_id** | **str** | ID of the child maintenance request | 
**maintenance_status** | **str** | Status of the child maintenance request | 
**maintenance_priority** | **str** | Priority level of the child work order | 
**maintenance_problem** | **str** | Problem related to the maintenance | 
**maintenance_location** | **str** | Location of the maintenance | [optional] 
**completed_on** | **str** | Completion date of the child work order | [optional] 
**entry_notes** | **str** | Entry notes for the child work order | [optional] 

## Example

```python
from openapi_client.models.get_work_orders_success_response_result_work_orders_work_order_inner_child_work_orders_child_work_order_inner import GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrdersChildWorkOrderInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrdersChildWorkOrderInner from a JSON string
get_work_orders_success_response_result_work_orders_work_order_inner_child_work_orders_child_work_order_inner_instance = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrdersChildWorkOrderInner.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrdersChildWorkOrderInner.to_json())

# convert the object into a dict
get_work_orders_success_response_result_work_orders_work_order_inner_child_work_orders_child_work_order_inner_dict = get_work_orders_success_response_result_work_orders_work_order_inner_child_work_orders_child_work_order_inner_instance.to_dict()
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrdersChildWorkOrderInner from a dict
get_work_orders_success_response_result_work_orders_work_order_inner_child_work_orders_child_work_order_inner_from_dict = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrdersChildWorkOrderInner.from_dict(get_work_orders_success_response_result_work_orders_work_order_inner_child_work_orders_child_work_order_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


