# GetVendorsSuccessResponseResultVendorsVendorInnerLocationsLocationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the location. | 
**name** | **str** | Name of the location. | 
**vendor_code** | **str** | Vendor code associated with the location. | 
**is_primary** | **str** | Indicates if this is the primary location. | 
**property_ids** | **str** | Comma-separated list of property IDs associated with this location. | 

## Example

```python
from entrata_api_client.models.get_vendors_success_response_result_vendors_vendor_inner_locations_location_inner import GetVendorsSuccessResponseResultVendorsVendorInnerLocationsLocationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerLocationsLocationInner from a JSON string
get_vendors_success_response_result_vendors_vendor_inner_locations_location_inner_instance = GetVendorsSuccessResponseResultVendorsVendorInnerLocationsLocationInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendorsVendorInnerLocationsLocationInner.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_vendor_inner_locations_location_inner_dict = get_vendors_success_response_result_vendors_vendor_inner_locations_location_inner_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerLocationsLocationInner from a dict
get_vendors_success_response_result_vendors_vendor_inner_locations_location_inner_from_dict = GetVendorsSuccessResponseResultVendorsVendorInnerLocationsLocationInner.from_dict(get_vendors_success_response_result_vendors_vendor_inner_locations_location_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


