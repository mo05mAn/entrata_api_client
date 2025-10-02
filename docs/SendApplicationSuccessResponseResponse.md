# SendApplicationSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary value sent with the request. | [optional] 
**code** | **int** | Successful response code. | 
**result** | [**SendApplicationSuccessResponseResponseResult**](SendApplicationSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_application_success_response_response import SendApplicationSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationSuccessResponseResponse from a JSON string
send_application_success_response_response_instance = SendApplicationSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendApplicationSuccessResponseResponse.to_json())

# convert the object into a dict
send_application_success_response_response_dict = send_application_success_response_response_instance.to_dict()
# create an instance of SendApplicationSuccessResponseResponse from a dict
send_application_success_response_response_from_dict = SendApplicationSuccessResponseResponse.from_dict(send_application_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


