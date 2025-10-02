# GetPoReceivingRecordsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_id** | **int** | This is an optional field. This field accepts single value. If \&quot;vendorId\&quot; is provided then \&quot;vendorCode\&quot; and \&quot;purchaseOrderNumbers\&quot; are not required. | [optional] 
**vendor_code** | **str** |   This is an optional field. This field accepts single value. If \&quot;vendorCode\&quot; is provided then \&quot;vendorId\&quot; and \&quot;purchaseOrderNumbers\&quot; are not required. | [optional] 
**purchase_order_numbers** | **int** | This is an optional field. This field accepts comma seperated multiple values. If \&quot;purchaseOrderNumbers\&quot; is provided then \&quot;vendorId\&quot; and \&quot;vendorCode\&quot; are not required. | [optional] 
**property_ids** | **str** |   This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**po_from_date** | **date** | This is an optional field. This field accepts single value. poFromDate and poToDate max range of 1 year | [optional] 
**po_to_date** | **date** | This is an optional field. This field accepts single value. poFromDate and poToDate max range of 1 year | [optional] 
**received_from_date** | **date** | This is an optional field. This field accepts single value. if dates are provided in filter then vendorId, vendorCode or PO number s are not required, receivedFromDate and receivedToDate max range of 1 year | [optional] 
**received_to_date** | **date** | This is an optional field. This field accepts single value. if dates are provided in filter then vendorId, vendorCode or PO number s are not required, receivedFromDate and receivedToDate max range of 1 year | [optional] 

## Example

```python
from entrata_api_client.models.get_po_receiving_records_method_params import GetPoReceivingRecordsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsMethodParams from a JSON string
get_po_receiving_records_method_params_instance = GetPoReceivingRecordsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsMethodParams.to_json())

# convert the object into a dict
get_po_receiving_records_method_params_dict = get_po_receiving_records_method_params_instance.to_dict()
# create an instance of GetPoReceivingRecordsMethodParams from a dict
get_po_receiving_records_method_params_from_dict = GetPoReceivingRecordsMethodParams.from_dict(get_po_receiving_records_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


