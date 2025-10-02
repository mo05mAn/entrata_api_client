# GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the unit type amenity | [optional] 
**is_standard_amenity** | **str** | Indicates if the amenity is standard | [optional] 
**is_optional** | **str** | Indicates if the amenity is optional | [optional] 
**is_published** | **str** | Indicates if the amenity is published | [optional] 
**is_featured** | **str** | Indicates if the amenity is featured | [optional] 
**hide_rates** | **str** | Indicates if the rates are hidden | [optional] 
**show_description** | **str** | Indicates if the description is shown | [optional] 
**include_in_rent** | **str** | Indicates if the amenity is included in rent | [optional] 

## Example

```python
from openapi_client.models.get_amenities_success_response_result_amenities_unit_type_amenities_amenity_attributes import GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes from a JSON string
get_amenities_success_response_result_amenities_unit_type_amenities_amenity_attributes_instance = GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes.to_json())

# convert the object into a dict
get_amenities_success_response_result_amenities_unit_type_amenities_amenity_attributes_dict = get_amenities_success_response_result_amenities_unit_type_amenities_amenity_attributes_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes from a dict
get_amenities_success_response_result_amenities_unit_type_amenities_amenity_attributes_from_dict = GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes.from_dict(get_amenities_success_response_result_amenities_unit_type_amenities_amenity_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


