# GetPropertiesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPropertiesMethodParams**](GetPropertiesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_properties_method import GetPropertiesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertiesMethod from a JSON string
get_properties_method_instance = GetPropertiesMethod.from_json(json)
# print the JSON string representation of the object
print(GetPropertiesMethod.to_json())

# convert the object into a dict
get_properties_method_dict = get_properties_method_instance.to_dict()
# create an instance of GetPropertiesMethod from a dict
get_properties_method_from_dict = GetPropertiesMethod.from_dict(get_properties_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


