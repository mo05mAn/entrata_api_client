# GetBudgetActuals


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetBudgetActualsMethod**](GetBudgetActualsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_budget_actuals import GetBudgetActuals

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetActuals from a JSON string
get_budget_actuals_instance = GetBudgetActuals.from_json(json)
# print the JSON string representation of the object
print(GetBudgetActuals.to_json())

# convert the object into a dict
get_budget_actuals_dict = get_budget_actuals_instance.to_dict()
# create an instance of GetBudgetActuals from a dict
get_budget_actuals_from_dict = GetBudgetActuals.from_dict(get_budget_actuals_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


