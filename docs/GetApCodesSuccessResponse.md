# GetApCodesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **int** | The response code indicating the status of the request. | 
**result** | [**GetApCodesSuccessResponseResult**](GetApCodesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_ap_codes_success_response import GetApCodesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetApCodesSuccessResponse from a JSON string
get_ap_codes_success_response_instance = GetApCodesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetApCodesSuccessResponse.to_json())

# convert the object into a dict
get_ap_codes_success_response_dict = get_ap_codes_success_response_instance.to_dict()
# create an instance of GetApCodesSuccessResponse from a dict
get_ap_codes_success_response_from_dict = GetApCodesSuccessResponse.from_dict(get_ap_codes_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


