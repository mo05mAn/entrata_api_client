# GetVendorPickListsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request. | 
**code** | **str** | Response code. | 
**result** | [**GetVendorPickListsSuccessResponseResult**](GetVendorPickListsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendor_pick_lists_success_response import GetVendorPickListsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorPickListsSuccessResponse from a JSON string
get_vendor_pick_lists_success_response_instance = GetVendorPickListsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetVendorPickListsSuccessResponse.to_json())

# convert the object into a dict
get_vendor_pick_lists_success_response_dict = get_vendor_pick_lists_success_response_instance.to_dict()
# create an instance of GetVendorPickListsSuccessResponse from a dict
get_vendor_pick_lists_success_response_from_dict = GetVendorPickListsSuccessResponse.from_dict(get_vendor_pick_lists_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


