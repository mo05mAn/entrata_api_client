# SendAmenitiesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. This field accepts a single integer value for Property ID | 
**name** | **str** | This is an optional field. This field accepts single value. This accepts name of the amenity | [optional] 
**description** | **str** | This is an optional field. This field accepts single value. This accepts description of the amenity. | [optional] 
**is_published** | **int** | This is an optional field. This field accepts single value. This flag accepts 1 or 0 ,whether amenity needs to be published or not . | [optional] 
**unit_space_id** | **int** | This is an optional field. This field accepts single value. This accepts unit space id for the amenity. | [optional] 

## Example

```python
from entrata_api_client.models.send_amenities_method_params import SendAmenitiesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenitiesMethodParams from a JSON string
send_amenities_method_params_instance = SendAmenitiesMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendAmenitiesMethodParams.to_json())

# convert the object into a dict
send_amenities_method_params_dict = send_amenities_method_params_instance.to_dict()
# create an instance of SendAmenitiesMethodParams from a dict
send_amenities_method_params_from_dict = SendAmenitiesMethodParams.from_dict(send_amenities_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


