# GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | Name of the contact. | 
**street_line1** | **str** | First line of the contact&#39;s street address. | [optional] 
**city** | **str** | City of the contact. | [optional] 
**state** | **str** | State of the contact. | [optional] 
**country** | **str** | Country of the contact. | [optional] 
**phone_number** | **str** | Phone number of the contact. | [optional] 
**email_address** | **str** | Email address of the contact. | [optional] 
**attributes** | [**GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInnerAttributes**](GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInnerAttributes.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendor_locations_success_response_result_locations_location_inner_contacts_contact_inner import GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInner from a JSON string
get_vendor_locations_success_response_result_locations_location_inner_contacts_contact_inner_instance = GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInner.to_json())

# convert the object into a dict
get_vendor_locations_success_response_result_locations_location_inner_contacts_contact_inner_dict = get_vendor_locations_success_response_result_locations_location_inner_contacts_contact_inner_instance.to_dict()
# create an instance of GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInner from a dict
get_vendor_locations_success_response_result_locations_location_inner_contacts_contact_inner_from_dict = GetVendorLocationsSuccessResponseResultLocationsLocationInnerContactsContactInner.from_dict(get_vendor_locations_success_response_result_locations_location_inner_contacts_contact_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


