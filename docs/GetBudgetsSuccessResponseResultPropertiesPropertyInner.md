# GetBudgetsSuccessResponseResultPropertiesPropertyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | The unique identifier for the property. | 
**property_name** | **str** | The name of the property. | 
**budgets** | [**GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets**](GetBudgetsSuccessResponseResultPropertiesPropertyInnerBudgets.md) |  | 

## Example

```python
from entrata_api_client.models.get_budgets_success_response_result_properties_property_inner import GetBudgetsSuccessResponseResultPropertiesPropertyInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInner from a JSON string
get_budgets_success_response_result_properties_property_inner_instance = GetBudgetsSuccessResponseResultPropertiesPropertyInner.from_json(json)
# print the JSON string representation of the object
print(GetBudgetsSuccessResponseResultPropertiesPropertyInner.to_json())

# convert the object into a dict
get_budgets_success_response_result_properties_property_inner_dict = get_budgets_success_response_result_properties_property_inner_instance.to_dict()
# create an instance of GetBudgetsSuccessResponseResultPropertiesPropertyInner from a dict
get_budgets_success_response_result_properties_property_inner_from_dict = GetBudgetsSuccessResponseResultPropertiesPropertyInner.from_dict(get_budgets_success_response_result_properties_property_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


