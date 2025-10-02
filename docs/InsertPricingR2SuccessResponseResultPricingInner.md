# InsertPricingR2SuccessResponseResultPricingInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | Unique identifier for the pricing node | 
**reference_id** | **str** | Reference ID associated with the pricing operation | 
**status** | **str** | Status of the pricing operation (e.g., &#39;Success&#39;) | 
**is_valid** | **str** | Indicates if the pricing is valid (e.g., &#39;Yes&#39;) | 
**message** | **str** | Message describing the result of the pricing operation | 

## Example

```python
from openapi_client.models.insert_pricing_r2_success_response_result_pricing_inner import InsertPricingR2SuccessResponseResultPricingInner

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingR2SuccessResponseResultPricingInner from a JSON string
insert_pricing_r2_success_response_result_pricing_inner_instance = InsertPricingR2SuccessResponseResultPricingInner.from_json(json)
# print the JSON string representation of the object
print(InsertPricingR2SuccessResponseResultPricingInner.to_json())

# convert the object into a dict
insert_pricing_r2_success_response_result_pricing_inner_dict = insert_pricing_r2_success_response_result_pricing_inner_instance.to_dict()
# create an instance of InsertPricingR2SuccessResponseResultPricingInner from a dict
insert_pricing_r2_success_response_result_pricing_inner_from_dict = InsertPricingR2SuccessResponseResultPricingInner.from_dict(insert_pricing_r2_success_response_result_pricing_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


