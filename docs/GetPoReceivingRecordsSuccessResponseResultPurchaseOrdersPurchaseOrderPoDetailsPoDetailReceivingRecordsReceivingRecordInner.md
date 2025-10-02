# GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the receiving record. | 
**property_id** | **int** | Property ID where the item was received. | 
**post_month_received** | **str** | Month when the item was received. | 
**receiver_name** | **str** | Name of the receiver. | 
**asset_location** | **str** | Location where the asset is stored. | 
**qty_received** | **str** | Quantity of items received. | 
**unit_cost** | **str** | Cost per unit of the received item. | 
**date_received** | **str** | Date when the item was received. | 
**qty_invoiced** | **str** | Quantity of items invoiced. | 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_receiving_record_inner import GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner from a JSON string
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_receiving_record_inner_instance = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_receiving_record_inner_dict = get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_receiving_record_inner_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner from a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_receiving_record_inner_from_dict = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner.from_dict(get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_receiving_record_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


