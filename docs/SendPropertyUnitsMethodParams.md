# SendPropertyUnitsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**unit_number** | **str** | This is a required field. This field accepts single value. This node should accept the unitNumber. | 
**unit_prefix** | **str** | This is an optional field. This field accepts single value. This node should accept the unitNunber prefix | [optional] 
**unit_suffix** | **str** | This is an optional field. This field accepts single value. This node should accept the unitNumber suffix | [optional] 
**space_number** | **int** | This is an optional field. This field accepts single value. This node should accept the spaceNumber on added unit. | [optional] 
**max_occupants** | **int** | This is an optional field. This field accepts single value. This node should accepts the maxOccupants of the property units | [optional] 
**max_pets** | **int** | This is an optional field. This field accepts single value. This node should accepts the maxPets of the property units | [optional] 
**number_of_bed_rooms** | **int** | This is an optional field. This field accepts single value. This node should accepts the beds number of the property units | [optional] 
**number_of_bath_rooms** | **int** | This is an optional field. This field accepts single value. This node should accepts the bathRooms of the property units | [optional] 
**square_feet** | **int** | This is an optional field. This field accepts single value. This node should accept the squareFeet of the property units | [optional] 
**note** | **str** | This is an optional field. This field accepts single value. This node should accept the note added for the property units | [optional] 
**unit_gender_id** | **int** | This is an optional field. This field accepts single value. This node should accept the Id of the gender. The unitGenderId should be get from getPropertyPickLists. | [optional] 

## Example

```python
from openapi_client.models.send_property_units_method_params import SendPropertyUnitsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyUnitsMethodParams from a JSON string
send_property_units_method_params_instance = SendPropertyUnitsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendPropertyUnitsMethodParams.to_json())

# convert the object into a dict
send_property_units_method_params_dict = send_property_units_method_params_instance.to_dict()
# create an instance of SendPropertyUnitsMethodParams from a dict
send_property_units_method_params_from_dict = SendPropertyUnitsMethodParams.from_dict(send_property_units_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


