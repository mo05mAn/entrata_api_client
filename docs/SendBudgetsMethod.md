# SendBudgetsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendBudgetsMethodParams**](SendBudgetsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_budgets_method import SendBudgetsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetsMethod from a JSON string
send_budgets_method_instance = SendBudgetsMethod.from_json(json)
# print the JSON string representation of the object
print(SendBudgetsMethod.to_json())

# convert the object into a dict
send_budgets_method_dict = send_budgets_method_instance.to_dict()
# create an instance of SendBudgetsMethod from a dict
send_budgets_method_from_dict = SendBudgetsMethod.from_dict(send_budgets_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


