# InsertPricingR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**InsertPricingR2Method**](InsertPricingR2Method.md) |  | 

## Example

```python
from openapi_client.models.insert_pricing_r2 import InsertPricingR2

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingR2 from a JSON string
insert_pricing_r2_instance = InsertPricingR2.from_json(json)
# print the JSON string representation of the object
print(InsertPricingR2.to_json())

# convert the object into a dict
insert_pricing_r2_dict = insert_pricing_r2_instance.to_dict()
# create an instance of InsertPricingR2 from a dict
insert_pricing_r2_from_dict = InsertPricingR2.from_dict(insert_pricing_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


