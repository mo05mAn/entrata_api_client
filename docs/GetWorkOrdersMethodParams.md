# GetWorkOrdersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**work_order_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**property_unit_id** | **int** | This is an optional field. This field accepts single value. propertyUnitId | [optional] 
**vendor_id** | **int** | This is an optional field. This field accepts single value. vendorId | [optional] 
**lease_status_type_ids** | **int** | This is an optional field. This field accepts single value. leaseStatusTypeIds | [optional] 
**work_order_type_ids** | **int** | This is an optional field. This field accepts single value. workOrderTypeIds | [optional] 
**building_name** | **str** | This is an optional field. This field accepts single value. buildingName | [optional] 
**unit_number** | **str** | This is an optional field. This field accepts single value. Unit number | [optional] 
**maintenance_priority_id** | **int** | This is an optional field. This field accepts single value. maintenancePriorityId | [optional] 
**maintenance_category_id** | **int** | This is an optional field. This field accepts single value. maintenanceCategoryId | [optional] 
**maintenance_problem_id** | **int** | This is an optional field. This field accepts single value. maintenanceProblemId | [optional] 
**include_child_work_orders** | **int** | This is an optional field. This field accepts single value. includeChildWorkOrders | [optional] 
**include_deleted_work_orders** | **int** | This is an optional field. This field accepts single value. If this flag is set to Yes then we are returning deleted work orders i n the response else we are not. | [optional] 
**created_on_from_date** | **date** | This is an optional field. This field accepts single value. createdOnFromDate | [optional] 
**created_on_to_date** | **date** | This is an optional field. This field accepts single value. createdOnToDate | [optional] 
**last_updated_on_from_date** | **date** | This is an optional field. This field accepts single value. If Location, Category, Problem, Description, Priority, and Status are updated then only work order will be returned in this filter. | [optional] 
**last_updated_on_to_date** | **date** | This is an optional field. This field accepts single value. If Location, Category, Problem, Description, Priority, and Status are updated then only work order will be returned in this filter. | [optional] 
**completed_on_from_date** | **date** | This is an optional field. This field accepts single value. completedOnFromDate | [optional] 
**completed_on_to_date** | **date** | This is an optional field. This field accepts single value. completedOnToDate | [optional] 

## Example

```python
from openapi_client.models.get_work_orders_method_params import GetWorkOrdersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetWorkOrdersMethodParams from a JSON string
get_work_orders_method_params_instance = GetWorkOrdersMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetWorkOrdersMethodParams.to_json())

# convert the object into a dict
get_work_orders_method_params_dict = get_work_orders_method_params_instance.to_dict()
# create an instance of GetWorkOrdersMethodParams from a dict
get_work_orders_method_params_from_dict = GetWorkOrdersMethodParams.from_dict(get_work_orders_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


