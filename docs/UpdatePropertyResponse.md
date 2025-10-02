# UpdatePropertyResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdatePropertyResponseMethod**](UpdatePropertyResponseMethod.md) |  | 

## Example

```python
from openapi_client.models.update_property_response import UpdatePropertyResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyResponse from a JSON string
update_property_response_instance = UpdatePropertyResponse.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyResponse.to_json())

# convert the object into a dict
update_property_response_dict = update_property_response_instance.to_dict()
# create an instance of UpdatePropertyResponse from a dict
update_property_response_from_dict = UpdatePropertyResponse.from_dict(update_property_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


