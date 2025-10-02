# GetVendorsSuccessResponseResultVendorsVendorInnerContactsContactInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the contact. | 
**name_first** | **str** | First name of the contact. | 
**name_last** | **str** | Last name of the contact. | 
**email** | **str** | Email address of the contact. | 
**phone** | **str** | Phone number of the contact. | 
**position** | **str** | Position of the contact within the company. | 

## Example

```python
from openapi_client.models.get_vendors_success_response_result_vendors_vendor_inner_contacts_contact_inner import GetVendorsSuccessResponseResultVendorsVendorInnerContactsContactInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerContactsContactInner from a JSON string
get_vendors_success_response_result_vendors_vendor_inner_contacts_contact_inner_instance = GetVendorsSuccessResponseResultVendorsVendorInnerContactsContactInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendorsVendorInnerContactsContactInner.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_vendor_inner_contacts_contact_inner_dict = get_vendors_success_response_result_vendors_vendor_inner_contacts_contact_inner_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerContactsContactInner from a dict
get_vendors_success_response_result_vendors_vendor_inner_contacts_contact_inner_from_dict = GetVendorsSuccessResponseResultVendorsVendorInnerContactsContactInner.from_dict(get_vendors_success_response_result_vendors_vendor_inner_contacts_contact_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


