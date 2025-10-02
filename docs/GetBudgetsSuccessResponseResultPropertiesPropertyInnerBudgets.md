# GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**budget** | [**List[GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner]**](GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner.md) | A list of budget records for the property. | 

## Example

```python
from openapi_client.models.get_budgets_success_response_result_properties_property_inner_budgets import GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets from a JSON string
get_budgets_success_response_result_properties_property_inner_budgets_instance = GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets.from_json(json)
# print the JSON string representation of the object
print(GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets.to_json())

# convert the object into a dict
get_budgets_success_response_result_properties_property_inner_budgets_dict = get_budgets_success_response_result_properties_property_inner_budgets_instance.to_dict()
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets from a dict
get_budgets_success_response_result_properties_property_inner_budgets_from_dict = GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets.from_dict(get_budgets_success_response_result_properties_property_inner_budgets_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


