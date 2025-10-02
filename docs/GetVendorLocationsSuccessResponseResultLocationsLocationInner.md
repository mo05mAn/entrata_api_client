# GetVendorLocationsSuccessResponseResultLocationsLocationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_id** | **str** | Unique identifier for the vendor. | 
**vendor_name** | **str** | Name of the vendor. | 
**status** | **str** | Current status of the vendor. | 
**term** | **str** | Payment terms for the vendor. | 
**legal_entity** | [**GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity**](GetVendorLocationsSuccessResponseResultLocationsLocationInnerLegalEntity.md) |  | 
**properties** | [**GetVendorLocationsSuccessResponseResultLocationsLocationInnerProperties**](GetVendorLocationsSuccessResponseResultLocationsLocationInnerProperties.md) |  | 
**contacts** | [**GetVendorLocationsSuccessResponseResultLocationsLocationInnerContacts**](GetVendorLocationsSuccessResponseResultLocationsLocationInnerContacts.md) |  | 
**attributes** | [**GetVendorLocationsSuccessResponseResultLocationsLocationInnerAttributes**](GetVendorLocationsSuccessResponseResultLocationsLocationInnerAttributes.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendor_locations_success_response_result_locations_location_inner import GetVendorLocationsSuccessResponseResultLocationsLocationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsSuccessResponseResultLocationsLocationInner from a JSON string
get_vendor_locations_success_response_result_locations_location_inner_instance = GetVendorLocationsSuccessResponseResultLocationsLocationInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsSuccessResponseResultLocationsLocationInner.to_json())

# convert the object into a dict
get_vendor_locations_success_response_result_locations_location_inner_dict = get_vendor_locations_success_response_result_locations_location_inner_instance.to_dict()
# create an instance of GetVendorLocationsSuccessResponseResultLocationsLocationInner from a dict
get_vendor_locations_success_response_result_locations_location_inner_from_dict = GetVendorLocationsSuccessResponseResultLocationsLocationInner.from_dict(get_vendor_locations_success_response_result_locations_location_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


