# UpdateAmenitiesSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_amenities** | [**UpdateAmenitiesSuccessResponseResponseResultPropertyAmenities**](UpdateAmenitiesSuccessResponseResponseResultPropertyAmenities.md) |  | 
**floorplan_amenities** | [**UpdateAmenitiesSuccessResponseResponseResultFloorplanAmenities**](UpdateAmenitiesSuccessResponseResponseResultFloorplanAmenities.md) |  | 
**unit_type_amenities** | [**UpdateAmenitiesSuccessResponseResponseResultUnitTypeAmenities**](UpdateAmenitiesSuccessResponseResponseResultUnitTypeAmenities.md) |  | 
**unit_space_amenities** | [**UpdateAmenitiesSuccessResponseResponseResultUnitSpaceAmenities**](UpdateAmenitiesSuccessResponseResponseResultUnitSpaceAmenities.md) |  | 

## Example

```python
from openapi_client.models.update_amenities_success_response_response_result import UpdateAmenitiesSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateAmenitiesSuccessResponseResponseResult from a JSON string
update_amenities_success_response_response_result_instance = UpdateAmenitiesSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateAmenitiesSuccessResponseResponseResult.to_json())

# convert the object into a dict
update_amenities_success_response_response_result_dict = update_amenities_success_response_response_result_instance.to_dict()
# create an instance of UpdateAmenitiesSuccessResponseResponseResult from a dict
update_amenities_success_response_response_result_from_dict = UpdateAmenitiesSuccessResponseResponseResult.from_dict(update_amenities_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


