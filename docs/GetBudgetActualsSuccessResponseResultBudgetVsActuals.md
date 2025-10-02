# GetBudgetActualsSuccessResponseResultBudgetVsActuals


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**budget_vs_actual** | [**List[GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner]**](GetBudgetActualsSuccessResponseResultBudgetVsActualsBudgetVsActualInner.md) | A list of budget vs actual records. | 

## Example

```python
from entrata_api_client.models.get_budget_actuals_success_response_result_budget_vs_actuals import GetBudgetActualsSuccessResponseResultBudgetVsActuals

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetActualsSuccessResponseResultBudgetVsActuals from a JSON string
get_budget_actuals_success_response_result_budget_vs_actuals_instance = GetBudgetActualsSuccessResponseResultBudgetVsActuals.from_json(json)
# print the JSON string representation of the object
print(GetBudgetActualsSuccessResponseResultBudgetVsActuals.to_json())

# convert the object into a dict
get_budget_actuals_success_response_result_budget_vs_actuals_dict = get_budget_actuals_success_response_result_budget_vs_actuals_instance.to_dict()
# create an instance of GetBudgetActualsSuccessResponseResultBudgetVsActuals from a dict
get_budget_actuals_success_response_result_budget_vs_actuals_from_dict = GetBudgetActualsSuccessResponseResultBudgetVsActuals.from_dict(get_budget_actuals_success_response_result_budget_vs_actuals_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


