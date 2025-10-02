# UpdateBudgetsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**budgets** | [**UpdateBudgetsSuccessResponseResultBudgets**](UpdateBudgetsSuccessResponseResultBudgets.md) |  | 

## Example

```python
from openapi_client.models.update_budgets_success_response_result import UpdateBudgetsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateBudgetsSuccessResponseResult from a JSON string
update_budgets_success_response_result_instance = UpdateBudgetsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateBudgetsSuccessResponseResult.to_json())

# convert the object into a dict
update_budgets_success_response_result_dict = update_budgets_success_response_result_instance.to_dict()
# create an instance of UpdateBudgetsSuccessResponseResult from a dict
update_budgets_success_response_result_from_dict = UpdateBudgetsSuccessResponseResult.from_dict(update_budgets_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


