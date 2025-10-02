# GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the GL account. | 
**account_name** | **str** | The name of the GL account. | 
**account_number** | **str** | The account number for the GL account. | 
**gl_totals** | [**GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInnerGlTotals**](GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInnerGlTotals.md) |  | 
**budget_months** | [**GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInnerBudgetMonths**](GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInnerBudgetMonths.md) |  | 

## Example

```python
from entrata_api_client.models.get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_gl_accounts_gl_account_inner import GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInner from a JSON string
get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_gl_accounts_gl_account_inner_instance = GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInner.from_json(json)
# print the JSON string representation of the object
print(GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInner.to_json())

# convert the object into a dict
get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_gl_accounts_gl_account_inner_dict = get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_gl_accounts_gl_account_inner_instance.to_dict()
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInner from a dict
get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_gl_accounts_gl_account_inner_from_dict = GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccountsGlAccountInner.from_dict(get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_gl_accounts_gl_account_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


