# SendApplicationVehicles


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendApplicationVehiclesMethod**](SendApplicationVehiclesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_application_vehicles import SendApplicationVehicles

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationVehicles from a JSON string
send_application_vehicles_instance = SendApplicationVehicles.from_json(json)
# print the JSON string representation of the object
print(SendApplicationVehicles.to_json())

# convert the object into a dict
send_application_vehicles_dict = send_application_vehicles_instance.to_dict()
# create an instance of SendApplicationVehicles from a dict
send_application_vehicles_from_dict = SendApplicationVehicles.from_dict(send_application_vehicles_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


