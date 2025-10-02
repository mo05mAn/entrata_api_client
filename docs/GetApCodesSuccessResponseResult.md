# GetApCodesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_code_categories** | [**GetApCodesSuccessResponseResultApCodeCategories**](GetApCodesSuccessResponseResultApCodeCategories.md) |  | 

## Example

```python
from openapi_client.models.get_ap_codes_success_response_result import GetApCodesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodesSuccessResponseResult from a JSON string
get_ap_codes_success_response_result_instance = GetApCodesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetApCodesSuccessResponseResult.to_json())

# convert the object into a dict
get_ap_codes_success_response_result_dict = get_ap_codes_success_response_result_instance.to_dict()
# create an instance of GetApCodesSuccessResponseResult from a dict
get_ap_codes_success_response_result_from_dict = GetApCodesSuccessResponseResult.from_dict(get_ap_codes_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


