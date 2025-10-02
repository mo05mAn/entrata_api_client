# GetArCodesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary value sent with the request. | [optional] 
**code** | **int** | Successful response code. | 
**result** | [**GetArCodesSuccessResponseResponseResult**](GetArCodesSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_ar_codes_success_response_response import GetArCodesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetArCodesSuccessResponseResponse from a JSON string
get_ar_codes_success_response_response_instance = GetArCodesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetArCodesSuccessResponseResponse.to_json())

# convert the object into a dict
get_ar_codes_success_response_response_dict = get_ar_codes_success_response_response_instance.to_dict()
# create an instance of GetArCodesSuccessResponseResponse from a dict
get_ar_codes_success_response_response_from_dict = GetArCodesSuccessResponseResponse.from_dict(get_ar_codes_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


