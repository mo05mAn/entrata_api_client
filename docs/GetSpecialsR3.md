# GetSpecialsR3


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetSpecialsR3Method**](GetSpecialsR3Method.md) |  | 

## Example

```python
from openapi_client.models.get_specials_r3 import GetSpecialsR3

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR3 from a JSON string
get_specials_r3_instance = GetSpecialsR3.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR3.to_json())

# convert the object into a dict
get_specials_r3_dict = get_specials_r3_instance.to_dict()
# create an instance of GetSpecialsR3 from a dict
get_specials_r3_from_dict = GetSpecialsR3.from_dict(get_specials_r3_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


