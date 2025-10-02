# GetSpecialsR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetSpecialsR2Method**](GetSpecialsR2Method.md) |  | 

## Example

```python
from openapi_client.models.get_specials_r2 import GetSpecialsR2

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2 from a JSON string
get_specials_r2_instance = GetSpecialsR2.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2.to_json())

# convert the object into a dict
get_specials_r2_dict = get_specials_r2_instance.to_dict()
# create an instance of GetSpecialsR2 from a dict
get_specials_r2_from_dict = GetSpecialsR2.from_dict(get_specials_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


