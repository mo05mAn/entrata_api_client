# InsertPricingSuccessResponseResult

The result containing pricing details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing** | [**List[InsertPricingSuccessResponseResultPricingInner]**](InsertPricingSuccessResponseResultPricingInner.md) | List of pricing nodes | [optional] 

## Example

```python
from openapi_client.models.insert_pricing_success_response_result import InsertPricingSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingSuccessResponseResult from a JSON string
insert_pricing_success_response_result_instance = InsertPricingSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(InsertPricingSuccessResponseResult.to_json())

# convert the object into a dict
insert_pricing_success_response_result_dict = insert_pricing_success_response_result_instance.to_dict()
# create an instance of InsertPricingSuccessResponseResult from a dict
insert_pricing_success_response_result_from_dict = InsertPricingSuccessResponseResult.from_dict(insert_pricing_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


