# SendBudgetsSuccessResponseResultBudgets


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**budget** | [**List[SendBudgetsSuccessResponseResultBudgetsBudgetInner]**](SendBudgetsSuccessResponseResultBudgetsBudgetInner.md) |  | 

## Example

```python
from entrata_api_client.models.send_budgets_success_response_result_budgets import SendBudgetsSuccessResponseResultBudgets

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetsSuccessResponseResultBudgets from a JSON string
send_budgets_success_response_result_budgets_instance = SendBudgetsSuccessResponseResultBudgets.from_json(json)
# print the JSON string representation of the object
print(SendBudgetsSuccessResponseResultBudgets.to_json())

# convert the object into a dict
send_budgets_success_response_result_budgets_dict = send_budgets_success_response_result_budgets_instance.to_dict()
# create an instance of SendBudgetsSuccessResponseResultBudgets from a dict
send_budgets_success_response_result_budgets_from_dict = SendBudgetsSuccessResponseResultBudgets.from_dict(send_budgets_success_response_result_budgets_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


