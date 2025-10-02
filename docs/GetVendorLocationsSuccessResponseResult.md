# GetVendorLocationsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**locations** | [**GetVendorLocationsSuccessResponseResultLocations**](GetVendorLocationsSuccessResponseResultLocations.md) |  | [optional] 
**insurances** | [**GetVendorLocationsSuccessResponseResultInsurances**](GetVendorLocationsSuccessResponseResultInsurances.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_vendor_locations_success_response_result import GetVendorLocationsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsSuccessResponseResult from a JSON string
get_vendor_locations_success_response_result_instance = GetVendorLocationsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsSuccessResponseResult.to_json())

# convert the object into a dict
get_vendor_locations_success_response_result_dict = get_vendor_locations_success_response_result_instance.to_dict()
# create an instance of GetVendorLocationsSuccessResponseResult from a dict
get_vendor_locations_success_response_result_from_dict = GetVendorLocationsSuccessResponseResult.from_dict(get_vendor_locations_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


