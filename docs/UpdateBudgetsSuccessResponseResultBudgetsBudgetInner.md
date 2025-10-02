# UpdateBudgetsSuccessResponseResultBudgetsBudgetInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | The node identifier for the budget update. | 
**status** | **str** | The status of the budget update. | 
**message** | **str** | Message indicating the result of the budget update. | 

## Example

```python
from entrata_api_client.models.update_budgets_success_response_result_budgets_budget_inner import UpdateBudgetsSuccessResponseResultBudgetsBudgetInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateBudgetsSuccessResponseResultBudgetsBudgetInner from a JSON string
update_budgets_success_response_result_budgets_budget_inner_instance = UpdateBudgetsSuccessResponseResultBudgetsBudgetInner.from_json(json)
# print the JSON string representation of the object
print(UpdateBudgetsSuccessResponseResultBudgetsBudgetInner.to_json())

# convert the object into a dict
update_budgets_success_response_result_budgets_budget_inner_dict = update_budgets_success_response_result_budgets_budget_inner_instance.to_dict()
# create an instance of UpdateBudgetsSuccessResponseResultBudgetsBudgetInner from a dict
update_budgets_success_response_result_budgets_budget_inner_from_dict = UpdateBudgetsSuccessResponseResultBudgetsBudgetInner.from_dict(update_budgets_success_response_result_budgets_budget_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


