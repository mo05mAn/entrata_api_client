# InsertPricingR2MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**pricing** | [**List[InsertPricingR2MethodParamsPricingInner]**](InsertPricingR2MethodParamsPricingInner.md) | Array of pricing objects | 

## Example

```python
from openapi_client.models.insert_pricing_r2_method_params import InsertPricingR2MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of InsertPricingR2MethodParams from a JSON string
insert_pricing_r2_method_params_instance = InsertPricingR2MethodParams.from_json(json)
# print the JSON string representation of the object
print(InsertPricingR2MethodParams.to_json())

# convert the object into a dict
insert_pricing_r2_method_params_dict = insert_pricing_r2_method_params_instance.to_dict()
# create an instance of InsertPricingR2MethodParams from a dict
insert_pricing_r2_method_params_from_dict = InsertPricingR2MethodParams.from_dict(insert_pricing_r2_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


