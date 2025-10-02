# GetInvoicesR2MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**invoice_number** | **int** | This is an optional field. This field accepts single value. | [optional] 
**vendor_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**property_ids** | **str** |   This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**from_date** | **date** | This is an optional field. This field accepts single value. This is based on the Post Date of the invoice. | [optional] 
**to_date** | **date** | This is an optional field. This field accepts single value. This is based on the Post Date of the invoice. | [optional] 
**paid_invoice_from_date** | **date** | This is an optional field. This field accepts single value. filters the invoices which have the payment applied to them on or after the given date. | [optional] 
**paid_invoice_to_date** | **date** | This is an optional field. This field accepts single value. we are showing the invoices which have the payment applied to them on or before the given date. | [optional] 
**post_month** | **date** | This is an optional field. This field accepts single value. | [optional] 
**include_voided_payments** | **int** | This is an optional field. This field accepts single value. Returns voided payment details if provided as 1 | [optional] 
**voided_payment_from_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**voided_payment_to_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**include_exported** | **int** | This is an optional field. This field accepts single value. | [optional] 
**customer_refunds** | **int** | This is an optional field. This field accepts single value. | [optional] 
**invoice_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from openapi_client.models.get_invoices_r2_method_params import GetInvoicesR2MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2MethodParams from a JSON string
get_invoices_r2_method_params_instance = GetInvoicesR2MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2MethodParams.to_json())

# convert the object into a dict
get_invoices_r2_method_params_dict = get_invoices_r2_method_params_instance.to_dict()
# create an instance of GetInvoicesR2MethodParams from a dict
get_invoices_r2_method_params_from_dict = GetInvoicesR2MethodParams.from_dict(get_invoices_r2_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


