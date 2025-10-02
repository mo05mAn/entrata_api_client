# SendWorkOrdersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**customer_id** | **int** | This is an optional field. This field accepts single value. Customer Id | [optional] 
**lease_id** | **int** | This is an optional field. This field accepts single value. Lease ID | [optional] 
**unit_number** | **str** | This is an optional field. This field accepts single value. Unit mumber | [optional] 
**customer_first_name** | **str** | This is an optional field. This field accepts single value. Customer First Name | [optional] 
**customer_last_name** | **str** | This is an optional field. This field accepts single value. Customer Last Name | [optional] 
**main_phone_number** | **int** | This is a required field. This field accepts single value. Main contact phone number | 
**alt_phone_number** | **int** | This is an optional field. This field accepts single value. Alternate contact phone number | [optional] 
**email_address** | **str** | This is an optional field. This field accepts single value. Email Address | [optional] 
**permission_to_enter** | **int** | This is a required field. This field accepts single value. Permission to enter | 
**maintenance_location_id** | **int** | This is a required field. This field accepts single value. Maintenance location | 
**maintenance_category_id** | **int** | This is a required field. This field accepts single value. Maintenance Category Id | 
**maintenance_problem_id** | **int** | This is a required field. This field accepts single value. Maintenance problem | 
**sub_maintenance_problem_id** | **int** | This is an optional field. This field accepts single value. SubMaintenance problem | [optional] 
**maintenance_priority_id** | **int** | This is an optional field. This field accepts single value. Maintenance Priority | [optional] 
**problem_description** | **str** | This is a required field. This field accepts single value. Problem Description | 
**pets_description** | **str** | This is an optional field. This field accepts single value. Pets Description is required if the lease has pets or if permission t o enter is denied so that a reason why entry is not permitted can be e xplained or a pet warning given. | [optional] 
**building_name** | **str** | This is an optional field. This field accepts single value. buildingName | [optional] 
**assigned_to** | **int** | This is an optional field. This field accepts single value. assignedTo | [optional] 
**scheduled_start_date_time** | **date** | This is an optional field. This field accepts single value. scheduledStartDateTime | [optional] 
**scheduled_end_date_time** | **date** | This is an optional field. This field accepts single value. scheduledEndDateTime | [optional] 
**due_date** | **date** | This is an optional field. This field accepts single value. While optional by default, dueDate could become required depending on a property setting. | [optional] 
**is_floating_work_order** | **int** | This is an optional field. This field accepts single value. | [optional] 
**priority_order_num** | **int** | This is an optional field. This field accepts single value. Negative numbers not allowed. This parameter is not applicable to mos t clients and should not be used without first checking with Entrata. | [optional] 

## Example

```python
from entrata_api_client.models.send_work_orders_method_params import SendWorkOrdersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendWorkOrdersMethodParams from a JSON string
send_work_orders_method_params_instance = SendWorkOrdersMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendWorkOrdersMethodParams.to_json())

# convert the object into a dict
send_work_orders_method_params_dict = send_work_orders_method_params_instance.to_dict()
# create an instance of SendWorkOrdersMethodParams from a dict
send_work_orders_method_params_from_dict = SendWorkOrdersMethodParams.from_dict(send_work_orders_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


