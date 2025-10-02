# GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRentTermRentInnerAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_term** | **str** | Duration of the lease | 
**lease_term_id** | **int** | Unique identifier for the lease term | 
**lease_term_name** | **str** | Name of the lease term | 
**rent** | **str** | Rent for the unit for this lease term | 
**start_date** | **str** | Start date of the lease term | 
**end_date** | **str** | End date of the lease term | 
**space_option** | **str** | Space option for the unit | 
**is_sold_out** | **bool** | Whether the unit is sold out | 

## Example

```python
from openapi_client.models.get_unit_types_success_response_response_result_unit_types_unit_type_inner_rent_term_rent_inner_attributes import GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRentTermRentInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRentTermRentInnerAttributes from a JSON string
get_unit_types_success_response_response_result_unit_types_unit_type_inner_rent_term_rent_inner_attributes_instance = GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRentTermRentInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRentTermRentInnerAttributes.to_json())

# convert the object into a dict
get_unit_types_success_response_response_result_unit_types_unit_type_inner_rent_term_rent_inner_attributes_dict = get_unit_types_success_response_response_result_unit_types_unit_type_inner_rent_term_rent_inner_attributes_instance.to_dict()
# create an instance of GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRentTermRentInnerAttributes from a dict
get_unit_types_success_response_response_result_unit_types_unit_type_inner_rent_term_rent_inner_attributes_from_dict = GetUnitTypesSuccessResponseResponseResultUnitTypesUnitTypeInnerRentTermRentInnerAttributes.from_dict(get_unit_types_success_response_response_result_unit_types_unit_type_inner_rent_term_rent_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


