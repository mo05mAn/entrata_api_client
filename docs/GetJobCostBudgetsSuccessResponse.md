# GetJobCostBudgetsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**GetJobCostBudgetsSuccessResponseResult**](GetJobCostBudgetsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_job_cost_budgets_success_response import GetJobCostBudgetsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobCostBudgetsSuccessResponse from a JSON string
get_job_cost_budgets_success_response_instance = GetJobCostBudgetsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetJobCostBudgetsSuccessResponse.to_json())

# convert the object into a dict
get_job_cost_budgets_success_response_dict = get_job_cost_budgets_success_response_instance.to_dict()
# create an instance of GetJobCostBudgetsSuccessResponse from a dict
get_job_cost_budgets_success_response_from_dict = GetJobCostBudgetsSuccessResponse.from_dict(get_job_cost_budgets_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


