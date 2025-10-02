# GetSpecialsR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property ID for getting Specials | 

## Example

```python
from entrata_api_client.models.get_specials_r1_method_params import GetSpecialsR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR1MethodParams from a JSON string
get_specials_r1_method_params_instance = GetSpecialsR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR1MethodParams.to_json())

# convert the object into a dict
get_specials_r1_method_params_dict = get_specials_r1_method_params_instance.to_dict()
# create an instance of GetSpecialsR1MethodParams from a dict
get_specials_r1_method_params_from_dict = GetSpecialsR1MethodParams.from_dict(get_specials_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


