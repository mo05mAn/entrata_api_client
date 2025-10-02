# GetBudgetActualsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetBudgetActualsMethodParams**](GetBudgetActualsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_budget_actuals_method import GetBudgetActualsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetActualsMethod from a JSON string
get_budget_actuals_method_instance = GetBudgetActualsMethod.from_json(json)
# print the JSON string representation of the object
print(GetBudgetActualsMethod.to_json())

# convert the object into a dict
get_budget_actuals_method_dict = get_budget_actuals_method_instance.to_dict()
# create an instance of GetBudgetActualsMethod from a dict
get_budget_actuals_method_from_dict = GetBudgetActualsMethod.from_dict(get_budget_actuals_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


