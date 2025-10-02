# UpdateCustomersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | This is a required field. This field accepts single value. This should be the unique ID of the customer to be updated and they mu st be in at least an applicant or higher lease status. | 
**first_name** | **str** | This is an optional field. This field accepts single value. | [optional] 
**last_name** | **str** | This is an optional field. This field accepts single value. | [optional] 
**name_prefix** | **str** | This is an optional field. This field accepts single value. | [optional] 
**middle_name** | **str** | This is an optional field. This field accepts single value. | [optional] 
**maiden_name** | **str** | This is an optional field. This field accepts single value. | [optional] 
**name_suffix** | **str** | This is an optional field. This field accepts single value. | [optional] 
**email** | **str** | This is an optional field. This field accepts single value. | [optional] 
**birth_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**tax_number_type_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**tax_number** | **int** | This is an optional field. This field accepts single value. | [optional] 
**address_type_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**street_line1** | **str** | This is an optional field. This field accepts single value. | [optional] 
**street_line2** | **str** | This is an optional field. This field accepts single value. | [optional] 
**street_line3** | **str** | This is an optional field. This field accepts single value. | [optional] 
**city** | **str** | This is an optional field. This field accepts single value. | [optional] 
**country** | **str** | This is an optional field. This field accepts single value. | [optional] 
**state** | **str** | This is an optional field. This field accepts single value. | [optional] 
**postal_code** | **int** | This is an optional field. This field accepts single value. | [optional] 
**phone_number_type_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**is_primary** | **int** | This is an optional field. This field accepts single value. | [optional] 
**phone_number** | **int** | This is an optional field. This field accepts single value. | [optional] 
**company_identification_type_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**identification_value** | **str** | This is an optional field. This field accepts single value. | [optional] 
**id_expiration_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**state_code** | **str** | This is an optional field. This field accepts single value. | [optional] 
**country_code** | **str** | This is an optional field. This field accepts single value. \&quot;countryCode\&quot; is accepted under \&quot;companyIdentificationValue\&quot; node. | [optional] 

## Example

```python
from openapi_client.models.update_customers_method_params import UpdateCustomersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomersMethodParams from a JSON string
update_customers_method_params_instance = UpdateCustomersMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomersMethodParams.to_json())

# convert the object into a dict
update_customers_method_params_dict = update_customers_method_params_instance.to_dict()
# create an instance of UpdateCustomersMethodParams from a dict
update_customers_method_params_from_dict = UpdateCustomersMethodParams.from_dict(update_customers_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


