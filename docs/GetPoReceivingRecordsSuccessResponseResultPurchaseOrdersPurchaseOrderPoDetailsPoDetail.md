# GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetail


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the purchase order detail. | 
**catalog_item_name** | **str** | Name of the catalog item. | 
**qty_ordered** | **str** | Quantity of items ordered. | 
**unit_cost** | **str** | Cost per unit of the catalog item. | 
**receiving_records** | [**GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords**](GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords.md) |  | 
**cancelled_records** | [**GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecords**](GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecords.md) |  | 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail import GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetail

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetail from a JSON string
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_instance = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetail.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetail.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_dict = get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetail from a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_from_dict = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetail.from_dict(get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


