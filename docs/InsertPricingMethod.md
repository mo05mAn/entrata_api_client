# InsertPricingMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**InsertPricingMethodParams**](InsertPricingMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.insert_pricing_method import InsertPricingMethod

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingMethod from a JSON string
insert_pricing_method_instance = InsertPricingMethod.from_json(json)
# print the JSON string representation of the object
print(InsertPricingMethod.to_json())

# convert the object into a dict
insert_pricing_method_dict = insert_pricing_method_instance.to_dict()
# create an instance of InsertPricingMethod from a dict
insert_pricing_method_from_dict = InsertPricingMethod.from_dict(insert_pricing_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


