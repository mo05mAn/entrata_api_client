# GetBudgetsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. propertyIds | 
**budget_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. budgetIds | [optional] 
**budget_status_type_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. budgetStatusTypeIds | [optional] 
**fiscal_years** | **str** | This is an optional field. This field accepts comma seperated multiple values. fiscalYears | [optional] 

## Example

```python
from entrata_api_client.models.get_budgets_method_params import GetBudgetsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetsMethodParams from a JSON string
get_budgets_method_params_instance = GetBudgetsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetBudgetsMethodParams.to_json())

# convert the object into a dict
get_budgets_method_params_dict = get_budgets_method_params_instance.to_dict()
# create an instance of GetBudgetsMethodParams from a dict
get_budgets_method_params_from_dict = GetBudgetsMethodParams.from_dict(get_budgets_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


