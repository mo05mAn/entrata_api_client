# GetApCodesSuccessResponseResultApCodeCategories


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_code_category** | [**List[GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner]**](GetApCodesSuccessResponseResultApCodeCategoriesApCodeCategoryInner.md) | A list of accounts payable categories. | 

## Example

```python
from entrata_api_client.models.get_ap_codes_success_response_result_ap_code_categories import GetApCodesSuccessResponseResultApCodeCategories

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodesSuccessResponseResultApCodeCategories from a JSON string
get_ap_codes_success_response_result_ap_code_categories_instance = GetApCodesSuccessResponseResultApCodeCategories.from_json(json)
# print the JSON string representation of the object
print(GetApCodesSuccessResponseResultApCodeCategories.to_json())

# convert the object into a dict
get_ap_codes_success_response_result_ap_code_categories_dict = get_ap_codes_success_response_result_ap_code_categories_instance.to_dict()
# create an instance of GetApCodesSuccessResponseResultApCodeCategories from a dict
get_ap_codes_success_response_result_ap_code_categories_from_dict = GetApCodesSuccessResponseResultApCodeCategories.from_dict(get_ap_codes_success_response_result_ap_code_categories_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


