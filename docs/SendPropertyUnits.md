# SendPropertyUnits


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendPropertyUnitsMethod**](SendPropertyUnitsMethod.md) |  | 

## Example

```python
from openapi_client.models.send_property_units import SendPropertyUnits

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyUnits from a JSON string
send_property_units_instance = SendPropertyUnits.from_json(json)
# print the JSON string representation of the object
print(SendPropertyUnits.to_json())

# convert the object into a dict
send_property_units_dict = send_property_units_instance.to_dict()
# create an instance of SendPropertyUnits from a dict
send_property_units_from_dict = SendPropertyUnits.from_dict(send_property_units_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


