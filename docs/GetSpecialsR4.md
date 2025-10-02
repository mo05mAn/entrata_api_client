# GetSpecialsR4


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**UpdatePropertyMediaAuth**](UpdatePropertyMediaAuth.md) |  | 
**request_id** | **str** | An arbitrary value to relate with response | [optional] 
**method** | [**GetSpecialsR4Method**](GetSpecialsR4Method.md) |  | 

## Example

```python
from openapi_client.models.get_specials_r4 import GetSpecialsR4

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR4 from a JSON string
get_specials_r4_instance = GetSpecialsR4.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR4.to_json())

# convert the object into a dict
get_specials_r4_dict = get_specials_r4_instance.to_dict()
# create an instance of GetSpecialsR4 from a dict
get_specials_r4_from_dict = GetSpecialsR4.from_dict(get_specials_r4_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


