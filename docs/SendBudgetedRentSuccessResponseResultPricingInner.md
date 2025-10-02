# SendBudgetedRentSuccessResponseResultPricingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Unique identifier for the pricing node | 
**status** | **str** | Status of the pricing operation (e.g., &#39;Success&#39;) | 
**message** | **str** | Message describing the result of the pricing operation | 

## Example

```python
from openapi_client.models.send_budgeted_rent_success_response_result_pricing_inner import SendBudgetedRentSuccessResponseResultPricingInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetedRentSuccessResponseResultPricingInner from a JSON string
send_budgeted_rent_success_response_result_pricing_inner_instance = SendBudgetedRentSuccessResponseResultPricingInner.from_json(json)
# print the JSON string representation of the object
print(SendBudgetedRentSuccessResponseResultPricingInner.to_json())

# convert the object into a dict
send_budgeted_rent_success_response_result_pricing_inner_dict = send_budgeted_rent_success_response_result_pricing_inner_instance.to_dict()
# create an instance of SendBudgetedRentSuccessResponseResultPricingInner from a dict
send_budgeted_rent_success_response_result_pricing_inner_from_dict = SendBudgetedRentSuccessResponseResultPricingInner.from_dict(send_budgeted_rent_success_response_result_pricing_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


