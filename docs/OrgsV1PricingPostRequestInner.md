# OrgsV1PricingPostRequestInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendBudgetedRentMethod**](SendBudgetedRentMethod.md) |  | 

## Example

```python
from entrata_api_client.models.orgs_v1_pricing_post_request_inner import OrgsV1PricingPostRequestInner

# TODO update the JSON string below
json = "{}"
# create an instance of OrgsV1PricingPostRequestInner from a JSON string
orgs_v1_pricing_post_request_inner_instance = OrgsV1PricingPostRequestInner.from_json(json)
# print the JSON string representation of the object
print(OrgsV1PricingPostRequestInner.to_json())

# convert the object into a dict
orgs_v1_pricing_post_request_inner_dict = orgs_v1_pricing_post_request_inner_instance.to_dict()
# create an instance of OrgsV1PricingPostRequestInner from a dict
orgs_v1_pricing_post_request_inner_from_dict = OrgsV1PricingPostRequestInner.from_dict(orgs_v1_pricing_post_request_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


