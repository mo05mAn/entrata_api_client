# SendBudgetedRent


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendBudgetedRentMethod**](SendBudgetedRentMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_budgeted_rent import SendBudgetedRent

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetedRent from a JSON string
send_budgeted_rent_instance = SendBudgetedRent.from_json(json)
# print the JSON string representation of the object
print(SendBudgetedRent.to_json())

# convert the object into a dict
send_budgeted_rent_dict = send_budgeted_rent_instance.to_dict()
# create an instance of SendBudgetedRent from a dict
send_budgeted_rent_from_dict = SendBudgetedRent.from_dict(send_budgeted_rent_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


