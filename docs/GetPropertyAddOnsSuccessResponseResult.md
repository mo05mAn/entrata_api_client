# GetPropertyAddOnsSuccessResponseResult

Result containing the add-on details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency_code** | **str** | Currency code for pricing information | 
**add_ons** | [**GetPropertyAddOnsSuccessResponseResultAddOns**](GetPropertyAddOnsSuccessResponseResultAddOns.md) |  | 

## Example

```python
from openapi_client.models.get_property_add_ons_success_response_result import GetPropertyAddOnsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertyAddOnsSuccessResponseResult from a JSON string
get_property_add_ons_success_response_result_instance = GetPropertyAddOnsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPropertyAddOnsSuccessResponseResult.to_json())

# convert the object into a dict
get_property_add_ons_success_response_result_dict = get_property_add_ons_success_response_result_instance.to_dict()
# create an instance of GetPropertyAddOnsSuccessResponseResult from a dict
get_property_add_ons_success_response_result_from_dict = GetPropertyAddOnsSuccessResponseResult.from_dict(get_property_add_ons_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


