# GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the line item | 
**var_property** | [**GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInnerProperty**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInnerProperty.md) |  | 
**gl_account** | [**GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInnerGlAccount**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInnerGlAccount.md) |  | 
**quantity** | **str** | Quantity for the line item | 
**rate** | **str** | Rate for the line item | 
**amount** | **str** | Amount for the line item | 
**amount_due** | **str** | Amount due for the line item | 
**shipping_amount** | **str** | Shipping amount for the line item | 
**discount_amount** | **str** | Discount amount for the line item | 
**tax_amount** | **str** | Tax amount for the line item | 
**payment_ids** | **str** | Payment IDs associated with the line item | 

## Example

```python
from entrata_api_client.models.get_invoices_r1_success_response_result_invoices_invoice_line_items_lineitem_inner import GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner from a JSON string
get_invoices_r1_success_response_result_invoices_invoice_line_items_lineitem_inner_instance = GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_invoices_invoice_line_items_lineitem_inner_dict = get_invoices_r1_success_response_result_invoices_invoice_line_items_lineitem_inner_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner from a dict
get_invoices_r1_success_response_result_invoices_invoice_line_items_lineitem_inner_from_dict = GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner.from_dict(get_invoices_r1_success_response_result_invoices_invoice_line_items_lineitem_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


