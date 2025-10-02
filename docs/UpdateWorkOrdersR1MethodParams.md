# UpdateWorkOrdersR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**work_order_id** | **int** | This is a required field. This field accepts single value. | 
**lease_id** | **int** |   This is an optional field. This field accepts single value. | [optional] 
**customer_id** | **int** |   This is an optional field. This field accepts single value. | [optional] 
**maintenance_status_type_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**maintenance_priority_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**maintenance_location_id** | **int** | This is a required field. This field accepts single value. Maintenance location | [optional] 
**maintenance_category_id** | **int** | This is a required field. This field accepts single value. Maintenance Category Id | [optional] 
**maintenance_problem_id** | **int** | This is a required field. This field accepts single value. Maintenance problem | 
**sub_maintenance_problem_id** | **int** | This is an optional field. This field accepts single value. SubMaintenance problem | [optional] 
**main_phone_number** | **int** | This is a required field. This field accepts single value. Main contact phone number | [optional] 
**alt_phone_number** | **int** | This is an optional field. This field accepts single value. Alternate contact phone number | [optional] 
**email_address** | **str** | This is an optional field. This field accepts single value. Email Address | [optional] 
**problem_description** | **str** | This is a required field. This field accepts single value. Problem Description | [optional] 
**pets_description** | **str** | This is an optional field. This field accepts single value. Pets Description could become required if the lease has pets or if per mission to enter is denied so that a reason why entry is not permitted can be explained or a pet warning given. | [optional] 
**completed_date_time** | **date** | This is an optional field. This field accepts single value. | [optional] 
**closing_comments** | **str** | This is an optional field. This field accepts single value. | [optional] 
**scheduled_start_date** | **date** | This is an optional field. This field accepts single value. scheduledStartDate | [optional] 
**scheduled_end_date** | **date** | This is an optional field. This field accepts single value. scheduledEndDate | [optional] 
**vendor_id** | **int** | This is an optional field. This field accepts single value. vendorId | [optional] 
**parent_work_order_id** | **int** | This is an optional field. This field accepts single value. parentWorkOrderId | [optional] 
**assigned_to** | **int** | This is an optional field. This field accepts single value. assignedTo | [optional] 
**due_date** | **date** | This is an optional field. This field accepts single value. While optional by default, dueDate could become required depending on a property setting. | [optional] 
**unit_available_on_date** | **date** | This is an optional field. This field accepts single value. This will set the related unit&#x60;s available date. Only works for make ready type work orders and only if a scheduledEndDate is provided. Must be on or after the scheduledEndDate. | [optional] 
**priority_order_num** | **int** |   This is an optional field. This field accepts single value. Negative numbers not allowed. | [optional] 
**permission_to_enter** | **int** | This is a optional field. This field accepts single value. Permission to enter | [optional] 

## Example

```python
from entrata_api_client.models.update_work_orders_r1_method_params import UpdateWorkOrdersR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWorkOrdersR1MethodParams from a JSON string
update_work_orders_r1_method_params_instance = UpdateWorkOrdersR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateWorkOrdersR1MethodParams.to_json())

# convert the object into a dict
update_work_orders_r1_method_params_dict = update_work_orders_r1_method_params_instance.to_dict()
# create an instance of UpdateWorkOrdersR1MethodParams from a dict
update_work_orders_r1_method_params_from_dict = UpdateWorkOrdersR1MethodParams.from_dict(update_work_orders_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


