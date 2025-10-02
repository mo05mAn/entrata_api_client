# GetArCodes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetArCodesMethod**](GetArCodesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_ar_codes import GetArCodes

# TODO update the JSON string below
json = "{}"
# create an instance of GetArCodes from a JSON string
get_ar_codes_instance = GetArCodes.from_json(json)
# print the JSON string representation of the object
print(GetArCodes.to_json())

# convert the object into a dict
get_ar_codes_dict = get_ar_codes_instance.to_dict()
# create an instance of GetArCodes from a dict
get_ar_codes_from_dict = GetArCodes.from_dict(get_ar_codes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


