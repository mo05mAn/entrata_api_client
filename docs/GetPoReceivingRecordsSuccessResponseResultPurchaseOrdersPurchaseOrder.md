# GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrder


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**purchase_order_number** | **str** | The unique purchase order number. | 
**purchase_order_post_month** | **str** | The post month for the purchase order. | 
**po_details** | [**GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetails**](GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrderPoDetails.md) |  | 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_success_response_result_purchase_orders_purchase_order import GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrder

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrder from a JSON string
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_instance = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrder.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrder.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_dict = get_po_receiving_records_success_response_result_purchase_orders_purchase_order_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrder from a dict
get_po_receiving_records_success_response_result_purchase_orders_purchase_order_from_dict = GetPoReceivingRecordsSuccessResponseResultPurchaseOrdersPurchaseOrder.from_dict(get_po_receiving_records_success_response_result_purchase_orders_purchase_order_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


