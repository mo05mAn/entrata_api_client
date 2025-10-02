# GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the property amenity | 
**image_url** | **str** | URL to the image representing the amenity | [optional] 
**description** | **str** | Description of the amenity | 
**rates** | [**GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInnerRates**](GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInnerRates.md) |  | 
**attributes** | [**GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInnerAttributes**](GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInnerAttributes.md) |  | 

## Example

```python
from entrata_api_client.models.get_amenities_success_response_result_amenities_property_amenities_amenity_inner import GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInner from a JSON string
get_amenities_success_response_result_amenities_property_amenities_amenity_inner_instance = GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInner.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInner.to_json())

# convert the object into a dict
get_amenities_success_response_result_amenities_property_amenities_amenity_inner_dict = get_amenities_success_response_result_amenities_property_amenities_amenity_inner_instance.to_dict()
# create an instance of GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInner from a dict
get_amenities_success_response_result_amenities_property_amenities_amenity_inner_from_dict = GetAmenitiesSuccessResponseResultAmenitiesPropertyAmenitiesAmenityInner.from_dict(get_amenities_success_response_result_amenities_property_amenities_amenity_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


