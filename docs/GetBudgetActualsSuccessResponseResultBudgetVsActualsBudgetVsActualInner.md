# GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_name** | **str** | The name of the account. | 
**account_id** | **str** | The unique identifier for the account. | 
**mtd_actual_income** | **str** | The month-to-date actual income. | 
**mtd_budget_income** | **str** | The month-to-date budgeted income. | 
**mtd_variance** | **str** | The month-to-date variance between actual and budgeted income. | 
**mtd_percentage_variance** | **str** | The percentage variance for month-to-date income. | 
**ytd_actual_income** | **str** | The year-to-date actual income. | 
**ytd_budget_income** | **str** | The year-to-date budgeted income. | 
**ytd_variance** | **str** | The year-to-date variance between actual and budgeted income. | 
**ytd_percentage_variance** | **str** | The percentage variance for year-to-date income. | 
**annual_budget_income** | **str** | The annual budgeted income for the account. | 

## Example

```python
from openapi_client.models.get_budget_actuals_success_response_result_budget_vs_actuals_budget_vs_actual_inner import GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner from a JSON string
get_budget_actuals_success_response_result_budget_vs_actuals_budget_vs_actual_inner_instance = GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner.from_json(json)
# print the JSON string representation of the object
print(GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner.to_json())

# convert the object into a dict
get_budget_actuals_success_response_result_budget_vs_actuals_budget_vs_actual_inner_dict = get_budget_actuals_success_response_result_budget_vs_actuals_budget_vs_actual_inner_instance.to_dict()
# create an instance of GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner from a dict
get_budget_actuals_success_response_result_budget_vs_actuals_budget_vs_actual_inner_from_dict = GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner.from_dict(get_budget_actuals_success_response_result_budget_vs_actuals_budget_vs_actual_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


