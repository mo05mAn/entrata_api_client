# GetApCodes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetApCodesMethod**](GetApCodesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_ap_codes import GetApCodes

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodes from a JSON string
get_ap_codes_instance = GetApCodes.from_json(json)
# print the JSON string representation of the object
print(GetApCodes.to_json())

# convert the object into a dict
get_ap_codes_dict = get_ap_codes_instance.to_dict()
# create an instance of GetApCodes from a dict
get_ap_codes_from_dict = GetApCodes.from_dict(get_ap_codes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


