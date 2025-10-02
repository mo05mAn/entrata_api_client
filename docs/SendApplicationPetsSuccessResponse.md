# SendApplicationPetsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**SendApplicationPetsSuccessResponseResponse**](SendApplicationPetsSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.send_application_pets_success_response import SendApplicationPetsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationPetsSuccessResponse from a JSON string
send_application_pets_success_response_instance = SendApplicationPetsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendApplicationPetsSuccessResponse.to_json())

# convert the object into a dict
send_application_pets_success_response_dict = send_application_pets_success_response_instance.to_dict()
# create an instance of SendApplicationPetsSuccessResponse from a dict
send_application_pets_success_response_from_dict = SendApplicationPetsSuccessResponse.from_dict(send_application_pets_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


