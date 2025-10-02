# GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the remittance | 
**name** | **str** | Name of the remittance | 
**ap_payment_type_id** | **str** | ID for the payment type | 
**ap_payment_type** | **str** | Payment type | 
**street_line1** | **str** | Street address line 1 | 
**street_line2** | **str** | Street address line 2 | 
**street_line3** | **List[str]** | Additional street address lines | [optional] 
**city** | **str** | City | 
**state_code** | **str** | State code | 
**postal_code** | **str** | Postal code | 

## Example

```python
from openapi_client.models.get_invoices_r1_success_response_result_invoices_invoice_remittance import GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance from a JSON string
get_invoices_r1_success_response_result_invoices_invoice_remittance_instance = GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_invoices_invoice_remittance_dict = get_invoices_r1_success_response_result_invoices_invoice_remittance_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance from a dict
get_invoices_r1_success_response_result_invoices_invoice_remittance_from_dict = GetInvoicesR1SuccessResponseResultInvoicesInvoiceRemittance.from_dict(get_invoices_r1_success_response_result_invoices_invoice_remittance_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


