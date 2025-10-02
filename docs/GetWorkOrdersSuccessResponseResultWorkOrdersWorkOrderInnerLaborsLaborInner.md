# GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**employee_name** | **str** | Name of the employee performing the labor | 
**description** | **str** | Description of the labor | 
**labor_type** | **str** | Type of labor | 
**labor_type_id** | **str** | ID of the labor type | 
**start_date_time** | **str** | Start date and time of labor | 
**end_date_time** | **str** | End date and time of labor | 
**total_minutes** | **str** | Total minutes worked | 
**per_hour_rate** | **str** | Hourly rate of the labor | 
**total_charge** | **str** | Total charge for the labor | 

## Example

```python
from entrata_api_client.models.get_work_orders_success_response_result_work_orders_work_order_inner_labors_labor_inner import GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner from a JSON string
get_work_orders_success_response_result_work_orders_work_order_inner_labors_labor_inner_instance = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner.to_json())

# convert the object into a dict
get_work_orders_success_response_result_work_orders_work_order_inner_labors_labor_inner_dict = get_work_orders_success_response_result_work_orders_work_order_inner_labors_labor_inner_instance.to_dict()
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner from a dict
get_work_orders_success_response_result_work_orders_work_order_inner_labors_labor_inner_from_dict = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLaborsLaborInner.from_dict(get_work_orders_success_response_result_work_orders_work_order_inner_labors_labor_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


