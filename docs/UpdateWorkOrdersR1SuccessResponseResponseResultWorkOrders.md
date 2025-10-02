# UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrders

Work orders result containing the details of the work orders

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**work_order** | [**List[UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInner]**](UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrdersWorkOrderInner.md) | List of work order results | [optional] 

## Example

```python
from openapi_client.models.update_work_orders_r1_success_response_response_result_work_orders import UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrders

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrders from a JSON string
update_work_orders_r1_success_response_response_result_work_orders_instance = UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrders.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrders.to_json())

# convert the object into a dict
update_work_orders_r1_success_response_response_result_work_orders_dict = update_work_orders_r1_success_response_response_result_work_orders_instance.to_dict()
# create an instance of UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrders from a dict
update_work_orders_r1_success_response_response_result_work_orders_from_dict = UpdateWorkOrdersR1SuccessResponseResponseResultWorkOrders.from_dict(update_work_orders_r1_success_response_response_result_work_orders_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


