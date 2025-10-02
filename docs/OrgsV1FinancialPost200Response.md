# OrgsV1FinancialPost200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**UpdateBudgetsSuccessResponseResult**](UpdateBudgetsSuccessResponseResult.md) |  | 
**response** | [**GetGlTreesR2SuccessResponseResponse**](GetGlTreesR2SuccessResponseResponse.md) |  | [optional] 

## Example

```python
from openapi_client.models.orgs_v1_financial_post200_response import OrgsV1FinancialPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of OrgsV1FinancialPost200Response from a JSON string
orgs_v1_financial_post200_response_instance = OrgsV1FinancialPost200Response.from_json(json)
# print the JSON string representation of the object
print(OrgsV1FinancialPost200Response.to_json())

# convert the object into a dict
orgs_v1_financial_post200_response_dict = orgs_v1_financial_post200_response_instance.to_dict()
# create an instance of OrgsV1FinancialPost200Response from a dict
orgs_v1_financial_post200_response_from_dict = OrgsV1FinancialPost200Response.from_dict(orgs_v1_financial_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


