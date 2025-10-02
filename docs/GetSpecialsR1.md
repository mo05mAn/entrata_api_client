# GetSpecialsR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetSpecialsR1Method**](GetSpecialsR1Method.md) |  | 

## Example

```python
from openapi_client.models.get_specials_r1 import GetSpecialsR1

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR1 from a JSON string
get_specials_r1_instance = GetSpecialsR1.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR1.to_json())

# convert the object into a dict
get_specials_r1_dict = get_specials_r1_instance.to_dict()
# create an instance of GetSpecialsR1 from a dict
get_specials_r1_from_dict = GetSpecialsR1.from_dict(get_specials_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


