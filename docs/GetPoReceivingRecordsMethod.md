# GetPoReceivingRecordsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetPoReceivingRecordsMethodParams**](GetPoReceivingRecordsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_po_receiving_records_method import GetPoReceivingRecordsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsMethod from a JSON string
get_po_receiving_records_method_instance = GetPoReceivingRecordsMethod.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsMethod.to_json())

# convert the object into a dict
get_po_receiving_records_method_dict = get_po_receiving_records_method_instance.to_dict()
# create an instance of GetPoReceivingRecordsMethod from a dict
get_po_receiving_records_method_from_dict = GetPoReceivingRecordsMethod.from_dict(get_po_receiving_records_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


