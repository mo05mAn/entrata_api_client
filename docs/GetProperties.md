# GetProperties


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetPropertiesMethod**](GetPropertiesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_properties import GetProperties

# TODO update the JSON string below
json = "{}"
# create an instance of GetProperties from a JSON string
get_properties_instance = GetProperties.from_json(json)
# print the JSON string representation of the object
print(GetProperties.to_json())

# convert the object into a dict
get_properties_dict = get_properties_instance.to_dict()
# create an instance of GetProperties from a dict
get_properties_from_dict = GetProperties.from_dict(get_properties_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


