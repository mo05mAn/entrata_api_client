# GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**purchase_order_number** | **str** | The unique number assigned to the purchase order. | 
**purchase_order_type** | **str** | The type of purchase order (e.g., Standard, Catalog, Job/Contract). | 
**vendor** | [**GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerVendor**](GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerVendor.md) |  | 
**vendor_code** | **str** | The unique vendor code. | [optional] 
**vendor_location** | **str** | The location of the vendor. | [optional] 
**post_month** | **str** | The month when the purchase order was posted. | 
**post_date** | **str** | The date when the purchase order was posted. | 
**po_status_id** | **str** | The status ID of the purchase order. | 
**po_approval_type_id** | **str** | The approval type ID for the purchase order. | 
**routing_tag_id** | **str** | The routing tag ID for the purchase order. | 
**sub_total** | **str** | The subtotal amount for the purchase order. | 
**tax_amount** | **str** | The total tax amount for the purchase order. | [optional] 
**shipping_amount** | **str** | The shipping cost for the purchase order. | [optional] 
**discount_amount** | **str** | The discount amount for the purchase order. | [optional] 
**order_amount** | **str** | The total order amount. | 
**po_note** | **str** | A note or comment related to the purchase order. | 
**created_on** | **str** | The timestamp when the purchase order was created. | [optional] 
**attached_url** | **str** | URL attached to the purchase order. | [optional] 
**line_items** | [**GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItems**](GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInnerLineItems.md) |  | 

## Example

```python
from openapi_client.models.get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner import GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner from a JSON string
get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_instance = GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner.from_json(json)
# print the JSON string representation of the object
print(GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner.to_json())

# convert the object into a dict
get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_dict = get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_instance.to_dict()
# create an instance of GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner from a dict
get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_from_dict = GetPurchaseOrdersSuccessResponseResultPurchaseOrdersPurchaseOrderInner.from_dict(get_purchase_orders_success_response_result_purchase_orders_purchase_order_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


