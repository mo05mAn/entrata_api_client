# GetPoReceivingRecordsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**purchase_orders** | [**GetPoReceivingRecordsSuccessResponseResultPurchaseOrders**](GetPoReceivingRecordsSuccessResponseResultPurchaseOrders.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_success_response_result import GetPoReceivingRecordsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponseResult from a JSON string
get_po_receiving_records_success_response_result_instance = GetPoReceivingRecordsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponseResult.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_result_dict = get_po_receiving_records_success_response_result_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponseResult from a dict
get_po_receiving_records_success_response_result_from_dict = GetPoReceivingRecordsSuccessResponseResult.from_dict(get_po_receiving_records_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


