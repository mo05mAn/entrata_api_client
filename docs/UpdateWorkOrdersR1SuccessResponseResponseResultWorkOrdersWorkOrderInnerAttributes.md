# UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInnerAttributes

Attributes of the work order

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**work_order_id** | **str** | Unique identifier for the work order | [optional] 
**status** | **str** | The current status of the work order | [optional] 
**message** | **str** | Message detailing the outcome of the work order | [optional] 

## Example

```python
from openapi_client.models.update_work_orders_r1_success_response_response_result_work_orders_work_order_inner_attributes import UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInnerAttributes from a JSON string
update_work_orders_r1_success_response_response_result_work_orders_work_order_inner_attributes_instance = UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInnerAttributes.to_json())

# convert the object into a dict
update_work_orders_r1_success_response_response_result_work_orders_work_order_inner_attributes_dict = update_work_orders_r1_success_response_response_result_work_orders_work_order_inner_attributes_instance.to_dict()
# create an instance of UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInnerAttributes from a dict
update_work_orders_r1_success_response_response_result_work_orders_work_order_inner_attributes_from_dict = UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInnerAttributes.from_dict(update_work_orders_r1_success_response_response_result_work_orders_work_order_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


