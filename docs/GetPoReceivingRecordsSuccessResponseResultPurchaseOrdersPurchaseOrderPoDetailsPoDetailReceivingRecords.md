# GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**receiving_record** | [**List[GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner]**](GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReceivingRecordInner.md) |  | [optional] 
**unreceiving_record** | [**List[GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner]**](GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsUnreceivingRecordInner.md) |  | [optional] 
**return_record** | [**List[GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner]**](GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records import GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords from a JSON string
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_instance = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_dict = get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords from a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_from_dict = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecords.from_dict(get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


