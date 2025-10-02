# ErrorResponseResponseError


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **int** | error code one of the [ 1xx, 3xx, 4xx, 5xx ] | 
**message** | **str** | error details. | 

## Example

```python
from openapi_client.models.error_response_response_error import ErrorResponseResponseError

# TODO update the JSON string below
json = "{}"
# create an instance of ErrorResponseResponseError from a JSON string
error_response_response_error_instance = ErrorResponseResponseError.from_json(json)
# print the JSON string representation of the object
print(ErrorResponseResponseError.to_json())

# convert the object into a dict
error_response_response_error_dict = error_response_response_error_instance.to_dict()
# create an instance of ErrorResponseResponseError from a dict
error_response_response_error_from_dict = ErrorResponseResponseError.from_dict(error_response_response_error_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


