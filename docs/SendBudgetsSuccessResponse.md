# SendBudgetsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**SendBudgetsSuccessResponseResult**](SendBudgetsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_budgets_success_response import SendBudgetsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendBudgetsSuccessResponse from a JSON string
send_budgets_success_response_instance = SendBudgetsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendBudgetsSuccessResponse.to_json())

# convert the object into a dict
send_budgets_success_response_dict = send_budgets_success_response_instance.to_dict()
# create an instance of SendBudgetsSuccessResponse from a dict
send_budgets_success_response_from_dict = SendBudgetsSuccessResponse.from_dict(send_budgets_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


