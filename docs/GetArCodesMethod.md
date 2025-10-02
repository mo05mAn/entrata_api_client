# GetArCodesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetArCodesMethodParams**](GetArCodesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_ar_codes_method import GetArCodesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetArCodesMethod from a JSON string
get_ar_codes_method_instance = GetArCodesMethod.from_json(json)
# print the JSON string representation of the object
print(GetArCodesMethod.to_json())

# convert the object into a dict
get_ar_codes_method_dict = get_ar_codes_method_instance.to_dict()
# create an instance of GetArCodesMethod from a dict
get_ar_codes_method_from_dict = GetArCodesMethod.from_dict(get_ar_codes_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


