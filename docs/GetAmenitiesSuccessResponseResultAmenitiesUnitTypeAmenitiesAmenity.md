# GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenity


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the unit type amenity | 
**image_url** | **str** | URL to the image representing the amenity | [optional] 
**description** | **str** | Description of the amenity | 
**units** | [**GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnits**](GetAmenitiesSuccessResponseResultAmenitiesUnitAmenitiesAmenityUnits.md) |  | 
**attributes** | [**GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes**](GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenityAttributes.md) |  | 

## Example

```python
from openapi_client.models.get_amenities_success_response_result_amenities_unit_type_amenities_amenity import GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenity

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenity from a JSON string
get_amenities_success_response_result_amenities_unit_type_amenities_amenity_instance = GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenity.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenity.to_json())

# convert the object into a dict
get_amenities_success_response_result_amenities_unit_type_amenities_amenity_dict = get_amenities_success_response_result_amenities_unit_type_amenities_amenity_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenity from a dict
get_amenities_success_response_result_amenities_unit_type_amenities_amenity_from_dict = GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenitiesAmenity.from_dict(get_amenities_success_response_result_amenities_unit_type_amenities_amenity_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


