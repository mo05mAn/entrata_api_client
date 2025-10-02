# InsertPricingR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **str** | Success response code | 
**result** | [**InsertPricingR2SuccessResponseResult**](InsertPricingR2SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.insert_pricing_r2_success_response import InsertPricingR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingR2SuccessResponse from a JSON string
insert_pricing_r2_success_response_instance = InsertPricingR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(InsertPricingR2SuccessResponse.to_json())

# convert the object into a dict
insert_pricing_r2_success_response_dict = insert_pricing_r2_success_response_instance.to_dict()
# create an instance of InsertPricingR2SuccessResponse from a dict
insert_pricing_r2_success_response_from_dict = InsertPricingR2SuccessResponse.from_dict(insert_pricing_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


