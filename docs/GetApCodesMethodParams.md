# GetApCodesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_account_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**ap_code_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. Currently supporting only job cost (3) | [optional] 

## Example

```python
from entrata_api_client.models.get_ap_codes_method_params import GetApCodesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodesMethodParams from a JSON string
get_ap_codes_method_params_instance = GetApCodesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetApCodesMethodParams.to_json())

# convert the object into a dict
get_ap_codes_method_params_dict = get_ap_codes_method_params_instance.to_dict()
# create an instance of GetApCodesMethodParams from a dict
get_ap_codes_method_params_from_dict = GetApCodesMethodParams.from_dict(get_ap_codes_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


