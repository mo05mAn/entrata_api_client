# SendVendorsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendors** | [**SendVendorsSuccessResponseResultVendors**](SendVendorsSuccessResponseResultVendors.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_vendors_success_response_result import SendVendorsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendVendorsSuccessResponseResult from a JSON string
send_vendors_success_response_result_instance = SendVendorsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendVendorsSuccessResponseResult.to_json())

# convert the object into a dict
send_vendors_success_response_result_dict = send_vendors_success_response_result_instance.to_dict()
# create an instance of SendVendorsSuccessResponseResult from a dict
send_vendors_success_response_result_from_dict = SendVendorsSuccessResponseResult.from_dict(send_vendors_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


