# GetStatusSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | an arbitary value sent with the request. | [optional] 
**code** | **int** |  | 
**result** | [**GetStatusSuccessResponseResponseResult**](GetStatusSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_status_success_response_response import GetStatusSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetStatusSuccessResponseResponse from a JSON string
get_status_success_response_response_instance = GetStatusSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetStatusSuccessResponseResponse.to_json())

# convert the object into a dict
get_status_success_response_response_dict = get_status_success_response_response_instance.to_dict()
# create an instance of GetStatusSuccessResponseResponse from a dict
get_status_success_response_response_from_dict = GetStatusSuccessResponseResponse.from_dict(get_status_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


