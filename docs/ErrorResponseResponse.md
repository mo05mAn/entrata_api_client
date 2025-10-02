# ErrorResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**error** | [**ErrorResponseResponseError**](ErrorResponseResponseError.md) |  | 

## Example

```python
from openapi_client.models.error_response_response import ErrorResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of ErrorResponseResponse from a JSON string
error_response_response_instance = ErrorResponseResponse.from_json(json)
# print the JSON string representation of the object
print(ErrorResponseResponse.to_json())

# convert the object into a dict
error_response_response_dict = error_response_response_instance.to_dict()
# create an instance of ErrorResponseResponse from a dict
error_response_response_from_dict = ErrorResponseResponse.from_dict(error_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


