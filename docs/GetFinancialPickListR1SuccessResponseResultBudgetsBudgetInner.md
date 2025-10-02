# GetFinancialPickListR1SuccessResponseResultBudgetsBudgetInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique identifier for the budget. | 
**name** | **str** | The name of the budget. | 
**status_type_id** | **int** | The status type identifier for the budget. | 
**is_default** | **int** | Indicates if the budget is the default budget. | 
**status_type** | **str** | The status of the budget. | 

## Example

```python
from entrata_api_client.models.get_financial_pick_list_r1_success_response_result_budgets_budget_inner import GetFinancialPickListR1SuccessResponseResultBudgetsBudgetInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetFinancialPickListR1SuccessResponseResultBudgetsBudgetInner from a JSON string
get_financial_pick_list_r1_success_response_result_budgets_budget_inner_instance = GetFinancialPickListR1SuccessResponseResultBudgetsBudgetInner.from_json(json)
# print the JSON string representation of the object
print(GetFinancialPickListR1SuccessResponseResultBudgetsBudgetInner.to_json())

# convert the object into a dict
get_financial_pick_list_r1_success_response_result_budgets_budget_inner_dict = get_financial_pick_list_r1_success_response_result_budgets_budget_inner_instance.to_dict()
# create an instance of GetFinancialPickListR1SuccessResponseResultBudgetsBudgetInner from a dict
get_financial_pick_list_r1_success_response_result_budgets_budget_inner_from_dict = GetFinancialPickListR1SuccessResponseResultBudgetsBudgetInner.from_dict(get_financial_pick_list_r1_success_response_result_budgets_budget_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


