# GetApCodesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetApCodesMethodParams**](GetApCodesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_ap_codes_method import GetApCodesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodesMethod from a JSON string
get_ap_codes_method_instance = GetApCodesMethod.from_json(json)
# print the JSON string representation of the object
print(GetApCodesMethod.to_json())

# convert the object into a dict
get_ap_codes_method_dict = get_ap_codes_method_instance.to_dict()
# create an instance of GetApCodesMethod from a dict
get_ap_codes_method_from_dict = GetApCodesMethod.from_dict(get_ap_codes_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


