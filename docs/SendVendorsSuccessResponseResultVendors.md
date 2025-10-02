# SendVendorsSuccessResponseResultVendors


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor** | [**List[SendVendorsSuccessResponseResultVendorsVendorInner]**](SendVendorsSuccessResponseResultVendorsVendorInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_vendors_success_response_result_vendors import SendVendorsSuccessResponseResultVendors

# TODO update the JSON string below
json = "{}"
# create an instance of SendVendorsSuccessResponseResultVendors from a JSON string
send_vendors_success_response_result_vendors_instance = SendVendorsSuccessResponseResultVendors.from_json(json)
# print the JSON string representation of the object
print(SendVendorsSuccessResponseResultVendors.to_json())

# convert the object into a dict
send_vendors_success_response_result_vendors_dict = send_vendors_success_response_result_vendors_instance.to_dict()
# create an instance of SendVendorsSuccessResponseResultVendors from a dict
send_vendors_success_response_result_vendors_from_dict = SendVendorsSuccessResponseResultVendors.from_dict(send_vendors_success_response_result_vendors_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


