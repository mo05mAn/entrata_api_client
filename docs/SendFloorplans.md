# SendFloorplans


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendFloorplansMethod**](SendFloorplansMethod.md) |  | 

## Example

```python
from openapi_client.models.send_floorplans import SendFloorplans

# TODO update the JSON string below
json = "{}"
# create an instance of SendFloorplans from a JSON string
send_floorplans_instance = SendFloorplans.from_json(json)
# print the JSON string representation of the object
print(SendFloorplans.to_json())

# convert the object into a dict
send_floorplans_dict = send_floorplans_instance.to_dict()
# create an instance of SendFloorplans from a dict
send_floorplans_from_dict = SendFloorplans.from_dict(send_floorplans_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


