# SendApplicationVehiclesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vehicle_type_id** | **int** | This is a required field. This field accepts single value. Indicates the type of vehicle. Possible values are 1, 2, or 3 where 1 &#x3D; Primary, 2 &#x3D; Secondary, and 3 &#x3D; Other. | 

## Example

```python
from entrata_api_client.models.send_application_vehicles_method_params import SendApplicationVehiclesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationVehiclesMethodParams from a JSON string
send_application_vehicles_method_params_instance = SendApplicationVehiclesMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendApplicationVehiclesMethodParams.to_json())

# convert the object into a dict
send_application_vehicles_method_params_dict = send_application_vehicles_method_params_instance.to_dict()
# create an instance of SendApplicationVehiclesMethodParams from a dict
send_application_vehicles_method_params_from_dict = SendApplicationVehiclesMethodParams.from_dict(send_application_vehicles_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


