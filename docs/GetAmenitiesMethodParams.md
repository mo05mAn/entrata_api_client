# GetAmenitiesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**unit_number** | **int** | This is an optional field. This field accepts single value. Unit Number | [optional] 
**charge_code_type_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from entrata_api_client.models.get_amenities_method_params import GetAmenitiesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetAmenitiesMethodParams from a JSON string
get_amenities_method_params_instance = GetAmenitiesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetAmenitiesMethodParams.to_json())

# convert the object into a dict
get_amenities_method_params_dict = get_amenities_method_params_instance.to_dict()
# create an instance of GetAmenitiesMethodParams from a dict
get_amenities_method_params_from_dict = GetAmenitiesMethodParams.from_dict(get_amenities_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


