# SendApplicationEmployersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**SendApplicationEmployersSuccessResponseResponse**](SendApplicationEmployersSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.send_application_employers_success_response import SendApplicationEmployersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationEmployersSuccessResponse from a JSON string
send_application_employers_success_response_instance = SendApplicationEmployersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendApplicationEmployersSuccessResponse.to_json())

# convert the object into a dict
send_application_employers_success_response_dict = send_application_employers_success_response_instance.to_dict()
# create an instance of SendApplicationEmployersSuccessResponse from a dict
send_application_employers_success_response_from_dict = SendApplicationEmployersSuccessResponse.from_dict(send_application_employers_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


