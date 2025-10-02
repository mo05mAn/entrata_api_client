# SendAmenities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendAmenitiesMethod**](SendAmenitiesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_amenities import SendAmenities

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenities from a JSON string
send_amenities_instance = SendAmenities.from_json(json)
# print the JSON string representation of the object
print(SendAmenities.to_json())

# convert the object into a dict
send_amenities_dict = send_amenities_instance.to_dict()
# create an instance of SendAmenities from a dict
send_amenities_from_dict = SendAmenities.from_dict(send_amenities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


