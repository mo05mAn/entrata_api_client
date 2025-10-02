# UpdateVendorsSuccessResponseResultVendorsVendor1Attributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reference_id** | **str** | Unique identifier for the vendor update request. | [optional] 
**status** | **str** | Status of the vendor update. | [optional] 
**message** | **str** | Message indicating the result of the vendor update. | [optional] 

## Example

```python
from entrata_api_client.models.update_vendors_success_response_result_vendors_vendor1_attributes import UpdateVendorsSuccessResponseResultVendorsVendor1Attributes

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateVendorsSuccessResponseResultVendorsVendor1Attributes from a JSON string
update_vendors_success_response_result_vendors_vendor1_attributes_instance = UpdateVendorsSuccessResponseResultVendorsVendor1Attributes.from_json(json)
# print the JSON string representation of the object
print(UpdateVendorsSuccessResponseResultVendorsVendor1Attributes.to_json())

# convert the object into a dict
update_vendors_success_response_result_vendors_vendor1_attributes_dict = update_vendors_success_response_result_vendors_vendor1_attributes_instance.to_dict()
# create an instance of UpdateVendorsSuccessResponseResultVendorsVendor1Attributes from a dict
update_vendors_success_response_result_vendors_vendor1_attributes_from_dict = UpdateVendorsSuccessResponseResultVendorsVendor1Attributes.from_dict(update_vendors_success_response_result_vendors_vendor1_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


