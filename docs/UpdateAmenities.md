# UpdateAmenities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateAmenitiesMethod**](UpdateAmenitiesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_amenities import UpdateAmenities

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateAmenities from a JSON string
update_amenities_instance = UpdateAmenities.from_json(json)
# print the JSON string representation of the object
print(UpdateAmenities.to_json())

# convert the object into a dict
update_amenities_dict = update_amenities_instance.to_dict()
# create an instance of UpdateAmenities from a dict
update_amenities_from_dict = UpdateAmenities.from_dict(update_amenities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


