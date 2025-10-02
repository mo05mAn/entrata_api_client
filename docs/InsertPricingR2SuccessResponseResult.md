# InsertPricingR2SuccessResponseResult

The result containing pricing details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**pricing** | [**List[InsertPricingR2SuccessResponseResultPricingInner]**](InsertPricingR2SuccessResponseResultPricingInner.md) | List of pricing nodes | [optional] 

## Example

```python
from openapi_client.models.insert_pricing_r2_success_response_result import InsertPricingR2SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingR2SuccessResponseResult from a JSON string
insert_pricing_r2_success_response_result_instance = InsertPricingR2SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(InsertPricingR2SuccessResponseResult.to_json())

# convert the object into a dict
insert_pricing_r2_success_response_result_dict = insert_pricing_r2_success_response_result_instance.to_dict()
# create an instance of InsertPricingR2SuccessResponseResult from a dict
insert_pricing_r2_success_response_result_from_dict = InsertPricingR2SuccessResponseResult.from_dict(insert_pricing_r2_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


