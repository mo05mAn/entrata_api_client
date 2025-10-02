# GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodesApCodeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the accounts payable code. | 
**name** | **str** | The name of the accounts payable code. | 
**gl_account_id** | **str** | The general ledger account ID associated with the AP code. | 
**ap_code_type_id** | **str** | The ID representing the type of the accounts payable code. | 
**ap_code_type** | **str** | The type of the accounts payable code. | 

## Example

```python
from entrata_api_client.models.get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_ap_codes_ap_code_inner import GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodesApCodeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodesApCodeInner from a JSON string
get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_ap_codes_ap_code_inner_instance = GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodesApCodeInner.from_json(json)
# print the JSON string representation of the object
print(GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodesApCodeInner.to_json())

# convert the object into a dict
get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_ap_codes_ap_code_inner_dict = get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_ap_codes_ap_code_inner_instance.to_dict()
# create an instance of GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodesApCodeInner from a dict
get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_ap_codes_ap_code_inner_from_dict = GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodesApCodeInner.from_dict(get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_ap_codes_ap_code_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


