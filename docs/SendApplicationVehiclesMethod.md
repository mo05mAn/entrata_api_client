# SendApplicationVehiclesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendApplicationVehiclesMethodParams**](SendApplicationVehiclesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_application_vehicles_method import SendApplicationVehiclesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationVehiclesMethod from a JSON string
send_application_vehicles_method_instance = SendApplicationVehiclesMethod.from_json(json)
# print the JSON string representation of the object
print(SendApplicationVehiclesMethod.to_json())

# convert the object into a dict
send_application_vehicles_method_dict = send_application_vehicles_method_instance.to_dict()
# create an instance of SendApplicationVehiclesMethod from a dict
send_application_vehicles_method_from_dict = SendApplicationVehiclesMethod.from_dict(send_application_vehicles_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


