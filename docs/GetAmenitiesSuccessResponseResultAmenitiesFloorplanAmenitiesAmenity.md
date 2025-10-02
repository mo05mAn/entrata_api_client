# GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenity


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the floorplan amenity | 
**image_url** | **str** | URL to the image representing the amenity | [optional] 
**description** | **str** | Description of the amenity | 
**floorplans** | [**GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenityFloorplans**](GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenityFloorplans.md) |  | 
**attributes** | [**GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenityAttributes**](GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenityAttributes.md) |  | 

## Example

```python
from openapi_client.models.get_amenities_success_response_result_amenities_floorplan_amenities_amenity import GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenity

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenity from a JSON string
get_amenities_success_response_result_amenities_floorplan_amenities_amenity_instance = GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenity.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenity.to_json())

# convert the object into a dict
get_amenities_success_response_result_amenities_floorplan_amenities_amenity_dict = get_amenities_success_response_result_amenities_floorplan_amenities_amenity_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenity from a dict
get_amenities_success_response_result_amenities_floorplan_amenities_amenity_from_dict = GetAmenitiesSuccessResponseResultAmenitiesFloorplanAmenitiesAmenity.from_dict(get_amenities_success_response_result_amenities_floorplan_amenities_amenity_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


