# GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**maintenance_request_id** | **str** | ID of the maintenance request | 
**property_id** | **str** | ID of the property | 
**building_name** | **str** | Building name | 
**unit_number** | **str** | Unit number | 
**customer_id** | **str** | Customer ID | 
**name_first** | **str** | First name of the customer | 
**name_last** | **str** | Last name of the customer | 
**primary_phone_number** | **str** | Primary phone number of the customer | 
**alternate_phone_number** | **str** | Alternate phone number | [optional] 
**email_address** | **str** | Email address of the customer | [optional] 
**created_on** | **str** | Timestamp of when the request was created | 
**assigned_to** | **str** | Employee assigned to the work order | 
**maintenance_status** | **str** | Status of the maintenance request | 
**maintenance_priority** | **str** | Priority level of the work order | 
**maintenance_category_name** | **str** | Category of the maintenance request | 
**maintenance_problem** | **str** | Problem related to the maintenance | 
**maintenance_description** | **str** | Description of the maintenance issue | 
**labors** | [**GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors**](GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerLabors.md) |  | [optional] 
**scheduled_start_date** | **str** | Scheduled start date for the work order | [optional] 
**scheduled_end_date** | **str** | Scheduled end date for the work order | [optional] 
**due_date** | **str** | Due date for the work order | [optional] 
**is_floating** | **str** | Indicates if the work order is floating | [optional] 
**permission_to_enter** | **str** | Indicates if permission to enter is granted | [optional] 
**pet_info** | **str** | Information about pets at the location | [optional] 
**alarm_info** | **str** | Alarm information for the location | [optional] 
**maintenance_request_from** | **str** | Source of the maintenance request | [optional] 
**maintenance_request_by** | **str** | Person who created the maintenance request | [optional] 
**is_deleted** | **str** | Indicates if the work order has been deleted | [optional] 
**child_work_orders** | [**GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrders**](GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInnerChildWorkOrders.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_work_orders_success_response_result_work_orders_work_order_inner import GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner from a JSON string
get_work_orders_success_response_result_work_orders_work_order_inner_instance = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner.to_json())

# convert the object into a dict
get_work_orders_success_response_result_work_orders_work_order_inner_dict = get_work_orders_success_response_result_work_orders_work_order_inner_instance.to_dict()
# create an instance of GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner from a dict
get_work_orders_success_response_result_work_orders_work_order_inner_from_dict = GetWorkOrdersSuccessResponseResultWorkOrdersWorkOrderInner.from_dict(get_work_orders_success_response_result_work_orders_work_order_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


