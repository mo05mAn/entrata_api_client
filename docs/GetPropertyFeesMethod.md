# GetPropertyFeesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**params** | [**GetPropertyFeesMethodParams**](GetPropertyFeesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_property_fees_method import GetPropertyFeesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyFeesMethod from a JSON string
get_property_fees_method_instance = GetPropertyFeesMethod.from_json(json)
# print the JSON string representation of the object
print(GetPropertyFeesMethod.to_json())

# convert the object into a dict
get_property_fees_method_dict = get_property_fees_method_instance.to_dict()
# create an instance of GetPropertyFeesMethod from a dict
get_property_fees_method_from_dict = GetPropertyFeesMethod.from_dict(get_property_fees_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


