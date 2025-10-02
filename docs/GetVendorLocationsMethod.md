# GetVendorLocationsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetVendorLocationsMethodParams**](GetVendorLocationsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_vendor_locations_method import GetVendorLocationsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsMethod from a JSON string
get_vendor_locations_method_instance = GetVendorLocationsMethod.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsMethod.to_json())

# convert the object into a dict
get_vendor_locations_method_dict = get_vendor_locations_method_instance.to_dict()
# create an instance of GetVendorLocationsMethod from a dict
get_vendor_locations_method_from_dict = GetVendorLocationsMethod.from_dict(get_vendor_locations_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


