# GetArCodesSuccessResponseResponseResultArcodesArcodeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique identifier of the AR code. | 
**code** | **int** | The AR code value. | [optional] 
**name** | **str** | The name of the AR code. | [optional] 
**code_type** | **str** | The type of the AR code. | [optional] 
**charge_usage** | **str** | The usage of the charge. | [optional] 
**charge_timing** | **str** | The timing of the charge. | [optional] 
**associated_ledger** | **str** | The associated ledger for the AR code. | [optional] 
**debit_gl_account_id** | **int** | The debit GL account ID. | [optional] 
**credit_gl_account_id** | **int** | The credit GL account ID. | [optional] 
**display_as** | **str** | The display name for the AR code. | [optional] 
**is_disabled** | **bool** | Whether the AR code is disabled. | [optional] 
**is_entrata_disabled** | **bool** | Whether the AR code is disabled in Entrata. | [optional] 
**is_taxable** | **bool** | Whether the AR code is taxable. | [optional] 

## Example

```python
from openapi_client.models.get_ar_codes_success_response_response_result_arcodes_arcode_inner import GetArCodesSuccessResponseResponseResultArcodesArcodeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetArCodesSuccessResponseResponseResultArcodesArcodeInner from a JSON string
get_ar_codes_success_response_response_result_arcodes_arcode_inner_instance = GetArCodesSuccessResponseResponseResultArcodesArcodeInner.from_json(json)
# print the JSON string representation of the object
print(GetArCodesSuccessResponseResponseResultArcodesArcodeInner.to_json())

# convert the object into a dict
get_ar_codes_success_response_response_result_arcodes_arcode_inner_dict = get_ar_codes_success_response_response_result_arcodes_arcode_inner_instance.to_dict()
# create an instance of GetArCodesSuccessResponseResponseResultArcodesArcodeInner from a dict
get_ar_codes_success_response_response_result_arcodes_arcode_inner_from_dict = GetArCodesSuccessResponseResponseResultArcodesArcodeInner.from_dict(get_ar_codes_success_response_response_result_arcodes_arcode_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


