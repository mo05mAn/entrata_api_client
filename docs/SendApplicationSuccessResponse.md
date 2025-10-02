# SendApplicationSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**SendApplicationSuccessResponseResponse**](SendApplicationSuccessResponseResponse.md) |  | 

## Example

```python
from openapi_client.models.send_application_success_response import SendApplicationSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationSuccessResponse from a JSON string
send_application_success_response_instance = SendApplicationSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendApplicationSuccessResponse.to_json())

# convert the object into a dict
send_application_success_response_dict = send_application_success_response_instance.to_dict()
# create an instance of SendApplicationSuccessResponse from a dict
send_application_success_response_from_dict = SendApplicationSuccessResponse.from_dict(send_application_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


