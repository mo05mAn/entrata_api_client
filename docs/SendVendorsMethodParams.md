# SendVendorsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**business_name** | **str** | This is a required field. This field accepts single value. | 
**name_on_tax_return** | **str** | This is a required field. This field accepts single value. | 
**remittance_name** | **str** | This is a required field. This field accepts single value. | 
**ap_payment_type_id** | **int** | This is a required field. This field accepts single value. | 
**name_on_account** | **str** | This is a required field. This field accepts single value. Required only when the payment type is ACH(eCheck) | 
**routing_number** | **int** | This is a required field. This field accepts single value. Required only when the payment type is ACH(eCheck). Must be numeric wi th 9 digits long. | 
**account_number** | **int** | This is a required field. This field accepts single value. Required only when the payment type is ACH(eCheck) | 
**contact** | **str** | This is a required field. This field accepts single value. | 
**first_name** | **str** | This is a required field. This field accepts single value. | 
**last_name** | **str** | This is a required field. This field accepts single value. | 
**name** | **str** | This is a required field. This field accepts single value. Accepts the location name | 
**is_primary** | **int** | This is a required field. This field accepts single value. | 
**utility_bill_receipt_type_id** | **int** | This is an optional field. This field accepts single value | [optional] 
**external_id** | **str** | This is a required field. This field accepts single value. externalId | 

## Example

```python
from entrata_api_client.models.send_vendors_method_params import SendVendorsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendVendorsMethodParams from a JSON string
send_vendors_method_params_instance = SendVendorsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendVendorsMethodParams.to_json())

# convert the object into a dict
send_vendors_method_params_dict = send_vendors_method_params_instance.to_dict()
# create an instance of SendVendorsMethodParams from a dict
send_vendors_method_params_from_dict = SendVendorsMethodParams.from_dict(send_vendors_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


