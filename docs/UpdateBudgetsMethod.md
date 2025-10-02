# UpdateBudgetsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateBudgetsMethodParams**](UpdateBudgetsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.update_budgets_method import UpdateBudgetsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateBudgetsMethod from a JSON string
update_budgets_method_instance = UpdateBudgetsMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateBudgetsMethod.to_json())

# convert the object into a dict
update_budgets_method_dict = update_budgets_method_instance.to_dict()
# create an instance of UpdateBudgetsMethod from a dict
update_budgets_method_from_dict = UpdateBudgetsMethod.from_dict(update_budgets_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


