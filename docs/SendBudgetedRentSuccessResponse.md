# SendBudgetedRentSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Success response code | 
**result** | [**SendBudgetedRentSuccessResponseResult**](SendBudgetedRentSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_budgeted_rent_success_response import SendBudgetedRentSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetedRentSuccessResponse from a JSON string
send_budgeted_rent_success_response_instance = SendBudgetedRentSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendBudgetedRentSuccessResponse.to_json())

# convert the object into a dict
send_budgeted_rent_success_response_dict = send_budgeted_rent_success_response_instance.to_dict()
# create an instance of SendBudgetedRentSuccessResponse from a dict
send_budgeted_rent_success_response_from_dict = SendBudgetedRentSuccessResponse.from_dict(send_budgeted_rent_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


