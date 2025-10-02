# SendBudgetedRentMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendBudgetedRentMethodParams**](SendBudgetedRentMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_budgeted_rent_method import SendBudgetedRentMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetedRentMethod from a JSON string
send_budgeted_rent_method_instance = SendBudgetedRentMethod.from_json(json)
# print the JSON string representation of the object
print(SendBudgetedRentMethod.to_json())

# convert the object into a dict
send_budgeted_rent_method_dict = send_budgeted_rent_method_instance.to_dict()
# create an instance of SendBudgetedRentMethod from a dict
send_budgeted_rent_method_from_dict = SendBudgetedRentMethod.from_dict(send_budgeted_rent_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


