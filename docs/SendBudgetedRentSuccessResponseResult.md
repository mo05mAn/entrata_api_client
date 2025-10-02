# SendBudgetedRentSuccessResponseResult

The result containing pricing details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing** | [**List[SendBudgetedRentSuccessResponseResultPricingInner]**](SendBudgetedRentSuccessResponseResultPricingInner.md) | List of pricing nodes | [optional] 

## Example

```python
from entrata_api_client.models.send_budgeted_rent_success_response_result import SendBudgetedRentSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetedRentSuccessResponseResult from a JSON string
send_budgeted_rent_success_response_result_instance = SendBudgetedRentSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendBudgetedRentSuccessResponseResult.to_json())

# convert the object into a dict
send_budgeted_rent_success_response_result_dict = send_budgeted_rent_success_response_result_instance.to_dict()
# create an instance of SendBudgetedRentSuccessResponseResult from a dict
send_budgeted_rent_success_response_result_from_dict = SendBudgetedRentSuccessResponseResult.from_dict(send_budgeted_rent_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


