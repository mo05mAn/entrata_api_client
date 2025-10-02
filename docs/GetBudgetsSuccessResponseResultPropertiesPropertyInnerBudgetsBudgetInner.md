# GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the budget. | 
**budget_name** | **str** | The name of the budget. | 
**budget_status_type_id** | **str** | The status type of the budget. | 
**is_default** | **str** | Indicates if this is the default budget. | 
**fiscal_start_date** | **date** | The fiscal start date for the budget. | 
**fiscal_end_date** | **date** | The fiscal end date for the budget. | 
**fiscal_year** | **str** | The fiscal year for the budget. | 
**budget_total** | **str** | The total value of the budget. | 
**gl_accounts** | [**GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccounts**](GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInnerGlAccounts.md) |  | 

## Example

```python
from entrata_api_client.models.get_budgets_success_response_result_properties_property_inner_budgets_budget_inner import GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner from a JSON string
get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_instance = GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner.from_json(json)
# print the JSON string representation of the object
print(GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner.to_json())

# convert the object into a dict
get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_dict = get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_instance.to_dict()
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner from a dict
get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_from_dict = GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgetsBudgetInner.from_dict(get_budgets_success_response_result_properties_property_inner_budgets_budget_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


