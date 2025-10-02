# GetFinancialPickListR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**result** | [**GetFinancialPickListR2SuccessResponseResult**](GetFinancialPickListR2SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_financial_pick_list_r2_success_response import GetFinancialPickListR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetFinancialPickListR2SuccessResponse from a JSON string
get_financial_pick_list_r2_success_response_instance = GetFinancialPickListR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetFinancialPickListR2SuccessResponse.to_json())

# convert the object into a dict
get_financial_pick_list_r2_success_response_dict = get_financial_pick_list_r2_success_response_instance.to_dict()
# create an instance of GetFinancialPickListR2SuccessResponse from a dict
get_financial_pick_list_r2_success_response_from_dict = GetFinancialPickListR2SuccessResponse.from_dict(get_financial_pick_list_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


