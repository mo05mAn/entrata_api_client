# SendBudgetsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**budgets** | [**SendBudgetsSuccessResponseResultBudgets**](SendBudgetsSuccessResponseResultBudgets.md) |  | 

## Example

```python
from entrata_api_client.models.send_budgets_success_response_result import SendBudgetsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetsSuccessResponseResult from a JSON string
send_budgets_success_response_result_instance = SendBudgetsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendBudgetsSuccessResponseResult.to_json())

# convert the object into a dict
send_budgets_success_response_result_dict = send_budgets_success_response_result_instance.to_dict()
# create an instance of SendBudgetsSuccessResponseResult from a dict
send_budgets_success_response_result_from_dict = SendBudgetsSuccessResponseResult.from_dict(send_budgets_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


