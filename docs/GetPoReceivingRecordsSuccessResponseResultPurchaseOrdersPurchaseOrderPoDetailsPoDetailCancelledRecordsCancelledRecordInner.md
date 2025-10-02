# GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecordsCancelledRecordInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the cancelled record. | 
**property_id** | **int** | Property ID where the item was cancelled. | 
**qty_cancelled** | **str** | Quantity of items cancelled. | 
**unit_cost** | **str** | Cost per unit of the cancelled item. | 
**date_cancelled** | **str** | Date when the item was cancelled. | 
**post_month_cancelled** | **str** | Month when the cancellation was posted. | 
**cancelled_by** | **str** | Name of the person who cancelled the item. | 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_cancelled_records_cancelled_record_inner import GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecordsCancelledRecordInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecordsCancelledRecordInner from a JSON string
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_cancelled_records_cancelled_record_inner_instance = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecordsCancelledRecordInner.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecordsCancelledRecordInner.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_cancelled_records_cancelled_record_inner_dict = get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_cancelled_records_cancelled_record_inner_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecordsCancelledRecordInner from a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_cancelled_records_cancelled_record_inner_from_dict = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailCancelledRecordsCancelledRecordInner.from_dict(get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_cancelled_records_cancelled_record_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


