# GetBudgetActualsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**budget_vs_actuals** | [**GetBudgetActualsSuccessResponseResultBudgetVsActuals**](GetBudgetActualsSuccessResponseResultBudgetVsActuals.md) |  | 

## Example

```python
from entrata_api_client.models.get_budget_actuals_success_response_result import GetBudgetActualsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetActualsSuccessResponseResult from a JSON string
get_budget_actuals_success_response_result_instance = GetBudgetActualsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetBudgetActualsSuccessResponseResult.to_json())

# convert the object into a dict
get_budget_actuals_success_response_result_dict = get_budget_actuals_success_response_result_instance.to_dict()
# create an instance of GetBudgetActualsSuccessResponseResult from a dict
get_budget_actuals_success_response_result_from_dict = GetBudgetActualsSuccessResponseResult.from_dict(get_budget_actuals_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


