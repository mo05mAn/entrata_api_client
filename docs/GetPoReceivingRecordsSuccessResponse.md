# GetPoReceivingRecordsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request. | 
**code** | **str** | Success response code | 
**result** | [**GetPoReceivingRecordsSuccessResponseResult**](GetPoReceivingRecordsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_po_receiving_records_success_response import GetPoReceivingRecordsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPoReceivingRecordsSuccessResponse from a JSON string
get_po_receiving_records_success_response_instance = GetPoReceivingRecordsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetPoReceivingRecordsSuccessResponse.to_json())

# convert the object into a dict
get_po_receiving_records_success_response_dict = get_po_receiving_records_success_response_instance.to_dict()
# create an instance of GetPoReceivingRecordsSuccessResponse from a dict
get_po_receiving_records_success_response_from_dict = GetPoReceivingRecordsSuccessResponse.from_dict(get_po_receiving_records_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


