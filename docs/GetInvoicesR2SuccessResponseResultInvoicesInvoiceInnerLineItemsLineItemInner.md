# GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItemsLineItemInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Line item identifier | 
**description** | **str** | Description of the line item | 
**quantity** | **str** | Quantity of the item | 
**rate** | **str** | Rate per item | 
**amount** | **str** | Total amount for the line item | 
**amount_due** | **str** | Amount due for the line item | 
**maintenance_location_id** | **str** | Maintenance location ID | [optional] 
**department_id** | **str** | Department ID | [optional] 
**department_name** | **str** | Department name | [optional] 
**property_building_number** | **str** | Building number | [optional] 
**po_number** | **str** | Purchase order number | [optional] 
**custom_tag_id** | **str** | Custom tag ID | [optional] 
**custom_tag_name** | **str** | Custom tag name | [optional] 
**confidential** | **str** | Flag indicating if the line item is confidential | [optional] 
**is1099** | **str** | Flag indicating if the line item is 1099 | [optional] 
**billback** | **str** | Billback flag | [optional] 

## Example

```python
from entrata_api_client.models.get_invoices_r2_success_response_result_invoices_invoice_inner_line_items_line_item_inner import GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItemsLineItemInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItemsLineItemInner from a JSON string
get_invoices_r2_success_response_result_invoices_invoice_inner_line_items_line_item_inner_instance = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItemsLineItemInner.from_json(json)
# print the JSON string representation of the object
print(GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItemsLineItemInner.to_json())

# convert the object into a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_line_items_line_item_inner_dict = get_invoices_r2_success_response_result_invoices_invoice_inner_line_items_line_item_inner_instance.to_dict()
# create an instance of GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItemsLineItemInner from a dict
get_invoices_r2_success_response_result_invoices_invoice_inner_line_items_line_item_inner_from_dict = GetInvoicesR2SuccessResponseResultInvoicesInvoiceInnerLineItemsLineItemInner.from_dict(get_invoices_r2_success_response_result_invoices_invoice_inner_line_items_line_item_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


