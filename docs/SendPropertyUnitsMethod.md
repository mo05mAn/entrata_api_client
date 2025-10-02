# SendPropertyUnitsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendPropertyUnitsMethodParams**](SendPropertyUnitsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_property_units_method import SendPropertyUnitsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendPropertyUnitsMethod from a JSON string
send_property_units_method_instance = SendPropertyUnitsMethod.from_json(json)
# print the JSON string representation of the object
print(SendPropertyUnitsMethod.to_json())

# convert the object into a dict
send_property_units_method_dict = send_property_units_method_instance.to_dict()
# create an instance of SendPropertyUnitsMethod from a dict
send_property_units_method_from_dict = SendPropertyUnitsMethod.from_dict(send_property_units_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


