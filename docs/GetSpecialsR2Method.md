# GetSpecialsR2Method


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetSpecialsR1MethodParams**](GetSpecialsR1MethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_specials_r2_method import GetSpecialsR2Method

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2Method from a JSON string
get_specials_r2_method_instance = GetSpecialsR2Method.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2Method.to_json())

# convert the object into a dict
get_specials_r2_method_dict = get_specials_r2_method_instance.to_dict()
# create an instance of GetSpecialsR2Method from a dict
get_specials_r2_method_from_dict = GetSpecialsR2Method.from_dict(get_specials_r2_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


