# GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialRatesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**charge_code_id** | **str** | The charge code ID for the rate. | 
**charge_code_type_id** | **str** | The charge code type ID. | 
**amount** | **str** | The amount for the rate. | 
**show_on_website** | **bool** | Indicates whether the rate should be shown on the website. | [optional] 
**lease_term_id** | **str** | The ID of the lease term associated with the rate. | [optional] 

## Example

```python
from openapi_client.models.get_specials_r2_success_response_specials_property_specials_special_rates_inner import GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialRatesInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialRatesInner from a JSON string
get_specials_r2_success_response_specials_property_specials_special_rates_inner_instance = GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialRatesInner.from_json(json)
# print the JSON string representation of the object
print(GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialRatesInner.to_json())

# convert the object into a dict
get_specials_r2_success_response_specials_property_specials_special_rates_inner_dict = get_specials_r2_success_response_specials_property_specials_special_rates_inner_instance.to_dict()
# create an instance of GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialRatesInner from a dict
get_specials_r2_success_response_specials_property_specials_special_rates_inner_from_dict = GetSpecialsR2SuccessResponseSpecialsPropertySpecialsSpecialRatesInner.from_dict(get_specials_r2_success_response_specials_property_specials_special_rates_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


