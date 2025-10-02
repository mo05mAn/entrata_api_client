# UpdateBudgetsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**id** | **int** | This is a required field. This field accepts single value. | 
**month** | **date** | This is a required field. This field accepts single value. Accepts budget month in MM/YYYY format. | 
**amount** | **int** | This is a required field. This field accepts single value. | 

## Example

```python
from entrata_api_client.models.update_budgets_method_params import UpdateBudgetsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateBudgetsMethodParams from a JSON string
update_budgets_method_params_instance = UpdateBudgetsMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateBudgetsMethodParams.to_json())

# convert the object into a dict
update_budgets_method_params_dict = update_budgets_method_params_instance.to_dict()
# create an instance of UpdateBudgetsMethodParams from a dict
update_budgets_method_params_from_dict = UpdateBudgetsMethodParams.from_dict(update_budgets_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


