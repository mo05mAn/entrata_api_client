# GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**receiver_id** | **str** | Unique identifier for the receiver. | [optional] 
**property_id** | **int** | Property ID where the item was returned. | [optional] 
**credit_invoice_id** | **str** | Credit invoice ID associated with the return. | [optional] 
**qty_returned** | **str** | Quantity of items returned. | [optional] 
**unit_cost** | **str** | Cost per unit of the returned item. | [optional] 
**date_returned** | **str** | Date when the item was returned. | [optional] 
**post_month_returned** | **str** | Month when the return was posted. | [optional] 
**receiver_name** | **str** | Name of the person who received the return. | [optional] 
**asset_location** | **str** | Location where the returned asset is stored. | [optional] 

## Example

```python
from openapi_client.models.get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_return_record_inner import GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner from a JSON string
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_return_record_inner_instance = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_return_record_inner_dict = get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_return_record_inner_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner from a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_return_record_inner_from_dict = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetailsPoDetailReceivingRecordsReturnRecordInner.from_dict(get_po_receiving_records_success_response_result_purchase_orders_purchase_order_po_details_po_detail_receiving_records_return_record_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


