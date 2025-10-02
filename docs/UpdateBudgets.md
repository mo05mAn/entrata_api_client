# UpdateBudgets


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateBudgetsMethod**](UpdateBudgetsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_budgets import UpdateBudgets

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateBudgets from a JSON string
update_budgets_instance = UpdateBudgets.from_json(json)
# print the JSON string representation of the object
print(UpdateBudgets.to_json())

# convert the object into a dict
update_budgets_dict = update_budgets_instance.to_dict()
# create an instance of UpdateBudgets from a dict
update_budgets_from_dict = UpdateBudgets.from_dict(update_budgets_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


