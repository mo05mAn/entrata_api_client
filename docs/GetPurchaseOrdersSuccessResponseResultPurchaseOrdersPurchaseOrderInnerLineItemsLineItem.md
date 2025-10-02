# GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItem


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the line item. | 
**gl_account_id** | **str** | General ledger account ID. | 
**gl_account_number** | **str** | General ledger account number. | 
**catalog_item_name** | **str** | Name of the catalog item. | 
**catalog_item_number** | **str** | Unique number for the catalog item. | 
**contract_name** | **str** | Name of the contract associated with the line item. | 
**description** | **str** | Description of the line item. | 
**order_status** | **str** | Status of the order. | [optional] 
**order_quantity** | **str** | Quantity of items ordered. | 
**rate** | **str** | Price per unit for the ordered item. | 
**sub_total** | **str** | Subtotal amount for the line item. | 
**tax_amount** | **str** | Tax amount for the line item. | [optional] 
**shipping_amount** | **str** | Shipping cost for the line item. | [optional] 
**discount_amount** | **str** | Discount amount for the line item. | [optional] 
**order_amount** | **str** | Total amount for the line item. | 
**property_id** | **str** | Property ID associated with the line item. | 
**department_id** | **str** | Department ID for the line item. | 
**custom_tag_id** | **str** | Custom tag ID associated with the line item. | [optional] 
**custom_tag_name** | **str** | Custom tag name associated with the line item. | [optional] 
**custom_tag_code** | **str** | Custom tag code associated with the line item. | [optional] 
**is_confidential** | **str** | Indicates whether the line item is confidential. | [optional] 
**invoices** | [**GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItemInvoices**](GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItemInvoices.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_line_items_line_item import GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItem

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItem from a JSON string
get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_line_items_line_item_instance = GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItem.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItem.to_json())

# convert the object into a dict
get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_line_items_line_item_dict = get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_line_items_line_item_instance.to_dict()
# create an instance of GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItem from a dict
get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_line_items_line_item_from_dict = GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItemsLineItem.from_dict(get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_line_items_line_item_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


