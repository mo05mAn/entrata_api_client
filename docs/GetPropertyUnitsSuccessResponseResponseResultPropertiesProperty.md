# GetPropertyUnitsSuccessResponseResponseResultPropertiesProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | Unique identifier for the property | 
**property_name** | **str** | Name of the property | 
**remote_primary_key** | **str** | Identifier from the remote system | 
**unit_count** | **int** | Number of units in the property | 
**building_count** | **int** | Number of buildings in the property | 
**property_availability_url** | **str** | URL for checking property availability | 
**units** | [**GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnits**](GetPropertyUnitsSuccessResponseResponseResultPropertiesPropertyUnits.md) |  | 

## Example

```python
from entrata_api_client.models.get_property_units_success_response_response_result_properties_property import GetPropertyUnitsSuccessResponseResponseResultPropertiesProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesProperty from a JSON string
get_property_units_success_response_response_result_properties_property_instance = GetPropertyUnitsSuccessResponseResponseResultPropertiesProperty.from_json(json)
# print the JSON string representation of the object
print(GetPropertyUnitsSuccessResponseResponseResultPropertiesProperty.to_json())

# convert the object into a dict
get_property_units_success_response_response_result_properties_property_dict = get_property_units_success_response_response_result_properties_property_instance.to_dict()
# create an instance of GetPropertyUnitsSuccessResponseResponseResultPropertiesProperty from a dict
get_property_units_success_response_response_result_properties_property_from_dict = GetPropertyUnitsSuccessResponseResponseResultPropertiesProperty.from_dict(get_property_units_success_response_response_result_properties_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


