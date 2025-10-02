# SendBudgetsSuccessResponseResultBudgetsBudgetInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | The node identifier for the budget insertion. | 
**status** | **str** | The status of the budget insertion. | 
**message** | **str** | Message indicating the result of the budget insertion. | 

## Example

```python
from entrata_api_client.models.send_budgets_success_response_result_budgets_budget_inner import SendBudgetsSuccessResponseResultBudgetsBudgetInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetsSuccessResponseResultBudgetsBudgetInner from a JSON string
send_budgets_success_response_result_budgets_budget_inner_instance = SendBudgetsSuccessResponseResultBudgetsBudgetInner.from_json(json)
# print the JSON string representation of the object
print(SendBudgetsSuccessResponseResultBudgetsBudgetInner.to_json())

# convert the object into a dict
send_budgets_success_response_result_budgets_budget_inner_dict = send_budgets_success_response_result_budgets_budget_inner_instance.to_dict()
# create an instance of SendBudgetsSuccessResponseResultBudgetsBudgetInner from a dict
send_budgets_success_response_result_budgets_budget_inner_from_dict = SendBudgetsSuccessResponseResultBudgetsBudgetInner.from_dict(send_budgets_success_response_result_budgets_budget_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


