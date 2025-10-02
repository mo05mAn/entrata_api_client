# InsertPricingSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **str** | Success response code | 
**result** | [**InsertPricingSuccessResponseResult**](InsertPricingSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.insert_pricing_success_response import InsertPricingSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingSuccessResponse from a JSON string
insert_pricing_success_response_instance = InsertPricingSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(InsertPricingSuccessResponse.to_json())

# convert the object into a dict
insert_pricing_success_response_dict = insert_pricing_success_response_instance.to_dict()
# create an instance of InsertPricingSuccessResponse from a dict
insert_pricing_success_response_from_dict = InsertPricingSuccessResponse.from_dict(insert_pricing_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


