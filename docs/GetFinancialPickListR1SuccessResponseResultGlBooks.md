# GetFinancialPickListR1SuccessResponseResultGlBooks


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_book** | [**List[GetFinancialPickListR1SuccessResponseResultGlBooksGlBookInner]**](GetFinancialPickListR1SuccessResponseResultGlBooksGlBookInner.md) | A list of GL books. | 

## Example

```python
from entrata_api_client.models.get_financial_pick_list_r1_success_response_result_gl_books import GetFinancialPickListR1SuccessResponseResultGlBooks

# TODO update the JSON string below
json = "{}"
# create an instance of GetFinancialPickListR1SuccessResponseResultGlBooks from a JSON string
get_financial_pick_list_r1_success_response_result_gl_books_instance = GetFinancialPickListR1SuccessResponseResultGlBooks.from_json(json)
# print the JSON string representation of the object
print(GetFinancialPickListR1SuccessResponseResultGlBooks.to_json())

# convert the object into a dict
get_financial_pick_list_r1_success_response_result_gl_books_dict = get_financial_pick_list_r1_success_response_result_gl_books_instance.to_dict()
# create an instance of GetFinancialPickListR1SuccessResponseResultGlBooks from a dict
get_financial_pick_list_r1_success_response_result_gl_books_from_dict = GetFinancialPickListR1SuccessResponseResultGlBooks.from_dict(get_financial_pick_list_r1_success_response_result_gl_books_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


