# GetBudgetsSuccessResponseResultProperties


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**var_property** | [**List[GetBudgetsSuccessResponseResultPropertiesPropertyInner]**](GetBudgetsSuccessResponseResultPropertiesPropertyInner.md) | A list of properties with associated budget data. | 

## Example

```python
from entrata_api_client.models.get_budgets_success_response_result_properties import GetBudgetsSuccessResponseResultProperties

# TODO update the JSON string below
json = "{}"
# create an instance of GetBudgetsSuccessResponseResultProperties from a JSON string
get_budgets_success_response_result_properties_instance = GetBudgetsSuccessResponseResultProperties.from_json(json)
# print the JSON string representation of the object
print(GetBudgetsSuccessResponseResultProperties.to_json())

# convert the object into a dict
get_budgets_success_response_result_properties_dict = get_budgets_success_response_result_properties_instance.to_dict()
# create an instance of GetBudgetsSuccessResponseResultProperties from a dict
get_budgets_success_response_result_properties_from_dict = GetBudgetsSuccessResponseResultProperties.from_dict(get_budgets_success_response_result_properties_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


