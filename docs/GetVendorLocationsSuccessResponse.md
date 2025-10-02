# GetVendorLocationsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request. | 
**code** | **str** | Success response code. | 
**result** | [**GetVendorLocationsSuccessResponseResult**](GetVendorLocationsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendor_locations_success_response import GetVendorLocationsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorLocationsSuccessResponse from a JSON string
get_vendor_locations_success_response_instance = GetVendorLocationsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetVendorLocationsSuccessResponse.to_json())

# convert the object into a dict
get_vendor_locations_success_response_dict = get_vendor_locations_success_response_instance.to_dict()
# create an instance of GetVendorLocationsSuccessResponse from a dict
get_vendor_locations_success_response_from_dict = GetVendorLocationsSuccessResponse.from_dict(get_vendor_locations_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


