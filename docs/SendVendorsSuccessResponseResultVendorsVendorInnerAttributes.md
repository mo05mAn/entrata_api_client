# SendVendorsSuccessResponseResultVendorsVendorInnerAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_id** | **int** | Unique identifier for the vendor. | [optional] 
**status** | **str** | Status of the vendor insertion. | [optional] 
**message** | **str** | Message indicating the result of the vendor insertion. | [optional] 

## Example

```python
from entrata_api_client.models.send_vendors_success_response_result_vendors_vendor_inner_attributes import SendVendorsSuccessResponseResultVendorsVendorInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of SendVendorsSuccessResponseResultVendorsVendorInnerAttributes from a JSON string
send_vendors_success_response_result_vendors_vendor_inner_attributes_instance = SendVendorsSuccessResponseResultVendorsVendorInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(SendVendorsSuccessResponseResultVendorsVendorInnerAttributes.to_json())

# convert the object into a dict
send_vendors_success_response_result_vendors_vendor_inner_attributes_dict = send_vendors_success_response_result_vendors_vendor_inner_attributes_instance.to_dict()
# create an instance of SendVendorsSuccessResponseResultVendorsVendorInnerAttributes from a dict
send_vendors_success_response_result_vendors_vendor_inner_attributes_from_dict = SendVendorsSuccessResponseResultVendorsVendorInnerAttributes.from_dict(send_vendors_success_response_result_vendors_vendor_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


