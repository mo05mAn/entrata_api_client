# GetBudgetActualsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**gl_tree_id** | **int** | This is a required field. This field accepts single value. | 
**budget_id** | **int** | This is a required field. This field accepts single value. | 
**post_month_from** | **str** | This is a required field. This field accepts single value. MM/YYYY | 
**post_month_to** | **str** | This is a required field. This field accepts single value. MM/YYYY | 
**gl_book_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. glBookTypeIds | [optional] 
**budget_status_type_id** | **int** | This is an optional field. This field accepts single value. budgetStatusTypeId | [optional] 
**accounting_method** | **str** | This is a required field. This field accepts single value. accountingMethod | [optional] 

## Example

```python
from entrata_api_client.models.get_budget_actuals_method_params import GetBudgetActualsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetActualsMethodParams from a JSON string
get_budget_actuals_method_params_instance = GetBudgetActualsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetBudgetActualsMethodParams.to_json())

# convert the object into a dict
get_budget_actuals_method_params_dict = get_budget_actuals_method_params_instance.to_dict()
# create an instance of GetBudgetActualsMethodParams from a dict
get_budget_actuals_method_params_from_dict = GetBudgetActualsMethodParams.from_dict(get_budget_actuals_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


