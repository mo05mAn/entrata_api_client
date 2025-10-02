# SendVendorsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**SendVendorsSuccessResponseResult**](SendVendorsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_vendors_success_response import SendVendorsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendVendorsSuccessResponse from a JSON string
send_vendors_success_response_instance = SendVendorsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendVendorsSuccessResponse.to_json())

# convert the object into a dict
send_vendors_success_response_dict = send_vendors_success_response_instance.to_dict()
# create an instance of SendVendorsSuccessResponse from a dict
send_vendors_success_response_from_dict = SendVendorsSuccessResponse.from_dict(send_vendors_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


