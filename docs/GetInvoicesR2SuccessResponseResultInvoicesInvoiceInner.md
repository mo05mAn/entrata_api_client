# GetInvoicesR2SuccessResponseResultInvoicesInvoiceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the invoice | 
**is_on_hold** | **str** | Flag indicating whether the invoice is on hold | 
**invoice_number** | **str** | Invoice number | 
**invoice_type** | **str** | Type of the invoice | 
**var_date** | **str** | Date the invoice was created | 
**post_month** | **str** | Month when the invoice was posted | 
**post_status** | **str** | Status of the invoice posting | [optional] 
**reversal_invoice_id** | **int** | ID of the reversal invoice, if applicable | [optional] 
**due_date** | **str** | Due date of the invoice | 
**post_date** | **str** | Date when the invoice was posted | [optional] 
**invoice_note** | **str** | Note related to the invoice | [optional] 
**routing_tag_id** | **str** | Routing tag identifier | [optional] 
**routing_tag_name** | **str** | Name of the routing tag | [optional] 
**remittance** | [**GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance**](GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerRemittance.md) |  | 
**vendor** | [**GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor**](GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerVendor.md) |  | 
**account** | [**GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerAccount**](GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerAccount.md) |  | [optional] 
**invoice_payments** | [**GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePayments**](GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerInvoicePayments.md) |  | 
**sub_total** | **str** | Subtotal of the invoice | [optional] 
**tax_amount** | **str** | Tax amount for the invoice | [optional] 
**shipping_amount** | **str** | Shipping amount for the invoice | [optional] 
**discount_amount** | **str** | Discount amount on the invoice | [optional] 
**amount** | **str** | Total amount for the invoice | 
**amount_due** | **str** | Amount due for the invoice | 
**note** | **str** | Invoice note | [optional] 
**is_posted** | **str** | Flag indicating if the invoice has been posted | 
**retention** | **str** | Retention amount for the invoice | [optional] 
**line_items** | [**GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItems**](GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItems.md) |  | 

## Example

```python
from entrata_api_client.models.get_invoices_r2_success_response_result_invoices_invoice_inner import GetInvoicesR2SuccessResponseResultInvoicesInvoiceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInner from a JSON string
get_invoices_r2_success_response_result_invoices_invoice_inner_instance = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInner.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2SuccessResponseResultInvoicesInvoiceInner.to_json())

# convert the object into a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_dict = get_invoices_r2_success_response_result_invoices_invoice_inner_instance.to_dict()
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInner from a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_from_dict = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInner.from_dict(get_invoices_r2_success_response_result_invoices_invoice_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


