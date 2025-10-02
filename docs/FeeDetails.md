# FeeDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | Property identifier | [optional] 
**property_floorplan_id** | **str** | Floor plan identifier | [optional] 
**unit_type_id** | **str** | Unit type identifier | [optional] 
**unit_space_id** | **str** | Unit space identifier | [optional] 
**entrata_category_id** | **str** | Category identifier | [optional] 
**entrata_category** | **str** | Category name | [optional] 
**associated_item_id** | **str** | Associated item identifier | [optional] 
**associated_item** | **str** | Associated item name | [optional] 
**cascade_id** | **str** | Cascade identifier | [optional] 
**cascade_reference_id** | **str** | Cascade reference identifier | [optional] 
**cascade_reference_name** | **str** | Cascade reference name | [optional] 
**space_configuration_id** | **str** | Space configuration identifier | [optional] 
**space_configuration** | **str** | Space configuration name | [optional] 
**charge_code_id** | **str** | Charge code identifier | [optional] 
**charge_code_name** | **str** | Charge code name | [optional] 
**charge_code_description** | **str** | Charge code description | [optional] 
**charge_code_group_name** | **str** | Charge code group name | [optional] 
**lease_term_id** | **str** | Lease term identifier | [optional] 
**lease_term** | **str** | Lease term | [optional] 
**lease_start_window_id** | **str** | Lease start window identifier | [optional] 
**term_start_date** | **str** | Term start date | [optional] 
**term_end_date** | **str** | Term end date | [optional] 
**charge_timing_id** | **str** | Charge timing identifier | [optional] 
**charge_timing** | **str** | Charge timing name | [optional] 
**formula_id** | **str** | Formula identifier | [optional] 
**formula_reference_id** | **str** | Formula reference identifier | [optional] 
**rate_amount** | **str** | Rate amount | [optional] 
**rate_increase_increment** | **str** | Rate increase increment | [optional] 
**detailed_amount** | **str** | Detailed amount | [optional] 
**is_optional** | **str** | Optional flag (0 or 1) | [optional] 
**is_refundable** | **str** | Refundable flag (0 or 1) | [optional] 
**customer_relationship_id** | **str** | Customer relationship identifier | [optional] 
**customer_relationship_name** | **str** | Customer relationship name | [optional] 

## Example

```python
from openapi_client.models.fee_details import FeeDetails

# TODO update the JSON string below
json = "{}"
# create an instance of FeeDetails from a JSON string
fee_details_instance = FeeDetails.from_json(json)
# print the JSON string representation of the object
print(FeeDetails.to_json())

# convert the object into a dict
fee_details_dict = fee_details_instance.to_dict()
# create an instance of FeeDetails from a dict
fee_details_from_dict = FeeDetails.from_dict(fee_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


