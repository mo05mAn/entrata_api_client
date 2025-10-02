# GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lineitem** | [**List[GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner]**](GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItemsLineitemInner.md) | List of line items for the invoice | 

## Example

```python
from entrata_api_client.models.get_invoices_r1_success_response_result_invoices_invoice_line_items import GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems from a JSON string
get_invoices_r1_success_response_result_invoices_invoice_line_items_instance = GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems.to_json())

# convert the object into a dict
get_invoices_r1_success_response_result_invoices_invoice_line_items_dict = get_invoices_r1_success_response_result_invoices_invoice_line_items_instance.to_dict()
# create an instance of GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems from a dict
get_invoices_r1_success_response_result_invoices_invoice_line_items_from_dict = GetInvoicesR1SuccessResponseResultInvoicesInvoiceLineItems.from_dict(get_invoices_r1_success_response_result_invoices_invoice_line_items_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


