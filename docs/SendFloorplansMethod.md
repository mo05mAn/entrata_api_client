# SendFloorplansMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendFloorplansMethodParams**](SendFloorplansMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_floorplans_method import SendFloorplansMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendFloorplansMethod from a JSON string
send_floorplans_method_instance = SendFloorplansMethod.from_json(json)
# print the JSON string representation of the object
print(SendFloorplansMethod.to_json())

# convert the object into a dict
send_floorplans_method_dict = send_floorplans_method_instance.to_dict()
# create an instance of SendFloorplansMethod from a dict
send_floorplans_method_from_dict = SendFloorplansMethod.from_dict(send_floorplans_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


