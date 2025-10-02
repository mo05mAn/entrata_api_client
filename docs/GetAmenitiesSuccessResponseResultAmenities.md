# GetAmenitiesSuccessResponseResultAmenities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_amenities** | [**GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenities**](GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenities.md) |  | 
**unit_amenities** | [**GetAmenitiesSuccessResponseResultAmenitiesUnitAmenities**](GetAmenitiesSuccessResponseResultAmenitiesUnitAmenities.md) |  | 
**floorplan_amenities** | [**GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenities**](GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenities.md) |  | 
**unit_type_amenities** | [**GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenities**](GetAmenitiesSuccessResponseResultAmenitiesUnitTypeAmenities.md) |  | 

## Example

```python
from entrata_api_client.models.get_amenities_success_response_result_amenities import GetAmenitiesSuccessResponseResultAmenities

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponseResultAmenities from a JSON string
get_amenities_success_response_result_amenities_instance = GetAmenitiesSuccessResponseResultAmenities.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponseResultAmenities.to_json())

# convert the object into a dict
get_amenities_success_response_result_amenities_dict = get_amenities_success_response_result_amenities_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponseResultAmenities from a dict
get_amenities_success_response_result_amenities_from_dict = GetAmenitiesSuccessResponseResultAmenities.from_dict(get_amenities_success_response_result_amenities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


