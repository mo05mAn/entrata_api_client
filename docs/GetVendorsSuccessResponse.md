# GetVendorsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request. | 
**code** | **str** | Response code. | 
**result** | [**GetVendorsSuccessResponseResult**](GetVendorsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_vendors_success_response import GetVendorsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponse from a JSON string
get_vendors_success_response_instance = GetVendorsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponse.to_json())

# convert the object into a dict
get_vendors_success_response_dict = get_vendors_success_response_instance.to_dict()
# create an instance of GetVendorsSuccessResponse from a dict
get_vendors_success_response_from_dict = GetVendorsSuccessResponse.from_dict(get_vendors_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


