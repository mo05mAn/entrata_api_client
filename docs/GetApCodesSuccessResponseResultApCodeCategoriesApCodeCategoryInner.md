# GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the accounts payable category. | 
**name** | **str** | The name of the accounts payable category. | 
**ap_codes** | [**GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodes**](GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInnerApCodes.md) |  | 

## Example

```python
from openapi_client.models.get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner import GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner from a JSON string
get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_instance = GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner.from_json(json)
# print the JSON string representation of the object
print(GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner.to_json())

# convert the object into a dict
get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_dict = get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_instance.to_dict()
# create an instance of GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner from a dict
get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_from_dict = GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner.from_dict(get_ap_codes_success_response_result_ap_code_categories_ap_code_category_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


