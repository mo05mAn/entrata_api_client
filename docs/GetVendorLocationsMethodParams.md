# GetVendorLocationsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. List of comma separated propertyIds | [optional] 
**show_all_status** | **int** | This is an optional field. This field accepts single value. Boolean parameter to retrieve all vendors irrespective of status. | [optional] 
**include_intercompany_vendors** | **int** | This is an optional field. This field accepts single value. If provided as \&quot;0\&quot; then \&quot;Standard\&quot; types of Vendors will be rendered a nd if provided as \&quot;1\&quot; then \&quot;Standard\&quot; and \&quot;Intercompany\&quot; types of Vend ors will be returned. | [optional] 
**vendor_id** | **int** | This is an optional field. This field accepts single value. Provides details based on provided VendorId | [optional] 
**vendor_name** | **str** | This is an optional field. This field accepts single value. Provides details based on provided VendorName | [optional] 
**vendor_code** | **str** | This is an optional field. This field accepts single value. Provides details based on provided VendorCode | [optional] 
**last_modified_on** | **date** |   This is an optional field. This field accepts single value. Returns results based on the LastModifiedOn date of the vendor or any of its locations, contacts, remittances or legal entities. | [optional] 

## Example

```python
from openapi_client.models.get_vendor_locations_method_params import GetVendorLocationsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsMethodParams from a JSON string
get_vendor_locations_method_params_instance = GetVendorLocationsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsMethodParams.to_json())

# convert the object into a dict
get_vendor_locations_method_params_dict = get_vendor_locations_method_params_instance.to_dict()
# create an instance of GetVendorLocationsMethodParams from a dict
get_vendor_locations_method_params_from_dict = GetVendorLocationsMethodParams.from_dict(get_vendor_locations_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


