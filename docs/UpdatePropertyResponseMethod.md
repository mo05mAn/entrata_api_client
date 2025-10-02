# UpdatePropertyResponseMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdatePropertyResponseMethodParams**](UpdatePropertyResponseMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.update_property_response_method import UpdatePropertyResponseMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePropertyResponseMethod from a JSON string
update_property_response_method_instance = UpdatePropertyResponseMethod.from_json(json)
# print the JSON string representation of the object
print(UpdatePropertyResponseMethod.to_json())

# convert the object into a dict
update_property_response_method_dict = update_property_response_method_instance.to_dict()
# create an instance of UpdatePropertyResponseMethod from a dict
update_property_response_method_from_dict = UpdatePropertyResponseMethod.from_dict(update_property_response_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


