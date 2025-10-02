# GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the unreceived record. | [optional] 
**property_id** | **int** | Property ID where the item was unreceived. | [optional] 
**post_month_unreceived** | **str** | Month when the item was unreceived. | [optional] 
**unreceiver_name** | **str** | Name of the unreceiver. | [optional] 
**qty_unreceived** | **str** | Quantity of items unreceived. | [optional] 
**unit_cost** | **str** | Cost per unit of the unreceived item. | [optional] 
**date_unreceived** | **str** | Date when the item was unreceived. | [optional] 
**qty_invoiced** | **int** | Quantity of items invoiced. | [optional] 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_unreceiving_record_inner import GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner from a JSON string
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_unreceiving_record_inner_instance = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_unreceiving_record_inner_dict = get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_unreceiving_record_inner_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner from a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_unreceiving_record_inner_from_dict = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner.from_dict(get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_unreceiving_record_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


