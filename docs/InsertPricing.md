# InsertPricing


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**InsertPricingMethod**](InsertPricingMethod.md) |  | 

## Example

```python
from openapi_client.models.insert_pricing import InsertPricing

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricing from a JSON string
insert_pricing_instance = InsertPricing.from_json(json)
# print the JSON string representation of the object
print(InsertPricing.to_json())

# convert the object into a dict
insert_pricing_dict = insert_pricing_instance.to_dict()
# create an instance of InsertPricing from a dict
insert_pricing_from_dict = InsertPricing.from_dict(insert_pricing_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


