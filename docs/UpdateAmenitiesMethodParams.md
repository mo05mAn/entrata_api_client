# UpdateAmenitiesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | This is a required field. This field accepts single value. This node should accept the amenity id which needs to be updated | [optional] 
**name** | **str** | This is a required field. This field accepts single value. This node should accept the amenity name. | [optional] 
**description** | **str** | This is an optional field. This field accepts single value. This node should accept the amenity description. | [optional] 
**is_published** | **int** | This is an optional field. This field accepts single value. | [optional] 
**is_featured** | **int** | This is an optional field. This field accepts single value. | [optional] 
**show_on_quote** | **int** | This is an optional field. This field accepts single value. This node indicates if the amenities are visible on quotes or not. Th is flag is supported only for property and unit space amenities. | [optional] 
**hide_description** | **int** | This is an optional field. This field accepts single value. | [optional] 
**video_url** | **str** | This is an optional field. This field accepts single value. | [optional] 
**default_amenity_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**amenity_id** | **int** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.update_amenities_method_params import UpdateAmenitiesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateAmenitiesMethodParams from a JSON string
update_amenities_method_params_instance = UpdateAmenitiesMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateAmenitiesMethodParams.to_json())

# convert the object into a dict
update_amenities_method_params_dict = update_amenities_method_params_instance.to_dict()
# create an instance of UpdateAmenitiesMethodParams from a dict
update_amenities_method_params_from_dict = UpdateAmenitiesMethodParams.from_dict(update_amenities_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


