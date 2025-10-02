# UpdateBudgetsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**UpdateBudgetsSuccessResponseResult**](UpdateBudgetsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_budgets_success_response import UpdateBudgetsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateBudgetsSuccessResponse from a JSON string
update_budgets_success_response_instance = UpdateBudgetsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateBudgetsSuccessResponse.to_json())

# convert the object into a dict
update_budgets_success_response_dict = update_budgets_success_response_instance.to_dict()
# create an instance of UpdateBudgetsSuccessResponse from a dict
update_budgets_success_response_from_dict = UpdateBudgetsSuccessResponse.from_dict(update_budgets_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


