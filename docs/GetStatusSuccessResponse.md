# GetStatusSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetStatusSuccessResponseResponse**](GetStatusSuccessResponseResponse.md) |  | 

## Example

```python
from openapi_client.models.get_status_success_response import GetStatusSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetStatusSuccessResponse from a JSON string
get_status_success_response_instance = GetStatusSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetStatusSuccessResponse.to_json())

# convert the object into a dict
get_status_success_response_dict = get_status_success_response_instance.to_dict()
# create an instance of GetStatusSuccessResponse from a dict
get_status_success_response_from_dict = GetStatusSuccessResponse.from_dict(get_status_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


