# SendBudgetsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**budget_name** | **str** | This is a required field. This field accepts single value. | 
**fiscal_year** | **int** | This is a required field. This field accepts single value. | 
**fiscal_start_month** | **date** | This is a required field. This field accepts single value. Accepts fiscal start month in MM/YYYY format. | 
**fiscal_end_month** | **date** | This is a required field. This field accepts single value. Accepts fiscal end month in MM/YYYY format. | 
**id** | **int** | This is a required field. This field accepts single value. This node accepts GL account id. | 
**budget_month** | **date** | This is a required field. This field accepts single value. Accepts budget month in MM/YYYY format. | 
**amount** | **int** | This is a required field. This field accepts single value. | 

## Example

```python
from entrata_api_client.models.send_budgets_method_params import SendBudgetsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetsMethodParams from a JSON string
send_budgets_method_params_instance = SendBudgetsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendBudgetsMethodParams.to_json())

# convert the object into a dict
send_budgets_method_params_dict = send_budgets_method_params_instance.to_dict()
# create an instance of SendBudgetsMethodParams from a dict
send_budgets_method_params_from_dict = SendBudgetsMethodParams.from_dict(send_budgets_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


