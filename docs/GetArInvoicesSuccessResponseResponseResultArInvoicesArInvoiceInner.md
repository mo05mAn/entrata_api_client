# GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | A unique identifier for the invoice. | 
**property_id** | **int** | The identifier for the property associated with the invoice. | [optional] 
**unit_id** | **int** | The identifier for the unit associated with the invoice. | [optional] 
**lease_id** | **int** | The identifier for the lease associated with the invoice. | [optional] 
**invoice_number** | **int** | The invoice number, used to identify the invoice in the system. | [optional] 
**corrected_ar_invoice_id** | **int** | The identifier for the invoice that this one corrects, if applicable. | [optional] 
**invoice_date** | **str** | The date the invoice was issued. | [optional] 
**invoice_due_date** | **str** | The date the payment for the invoice is due. | [optional] 
**customer_id** | **str** | The unique identifier for the customer associated with the invoice. | [optional] 
**customer_name** | **str** | The name of the customer associated with the invoice. | [optional] 
**street_line1** | **str** | The first line of the customer&#39;s address. | [optional] 
**street_line2** | **str** | The second line of the customer&#39;s address. | [optional] 
**street_line3** | **str** | The third line of the customer&#39;s address. | [optional] 
**city** | **str** | The city where the customer resides. | [optional] 
**state** | **str** | The state where the customer resides. | [optional] 
**postal_code** | **str** | The postal code for the customer&#39;s address. | [optional] 
**country** | **str** | The country of the customer. | [optional] 
**note** | **str** | Any additional notes related to the invoice. | [optional] 
**invoice_type** | **str** | The type of invoice (e.g., Standard, Correction). | [optional] 
**invoice_sub_total** | **str** | The total before tax is applied to the invoice. | [optional] 
**total_tax_amount** | **int** | The total tax applied to the invoice. | [optional] 
**ar_transactions** | [**GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactions**](GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInnerArTransactions.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner import GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInner from a JSON string
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_instance = GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInner.from_json(json)
# print the JSON string representation of the object
print(GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInner.to_json())

# convert the object into a dict
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_dict = get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_instance.to_dict()
# create an instance of GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInner from a dict
get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_from_dict = GetArInvoicesSuccessResponseResponseResultArInvoicesArInvoiceInner.from_dict(get_ar_invoices_success_response_response_result_ar_invoices_ar_invoice_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


