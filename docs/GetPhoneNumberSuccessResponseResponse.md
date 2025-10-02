# GetPhoneNumberSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | an arbitary value sent with the request. | 
**code** | **int** | Response code indicating success | 
**result** | **Dict[str, str]** |  | 

## Example

```python
from openapi_client.models.get_phone_number_success_response_response import GetPhoneNumberSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetPhoneNumberSuccessResponseResponse from a JSON string
get_phone_number_success_response_response_instance = GetPhoneNumberSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetPhoneNumberSuccessResponseResponse.to_json())

# convert the object into a dict
get_phone_number_success_response_response_dict = get_phone_number_success_response_response_instance.to_dict()
# create an instance of GetPhoneNumberSuccessResponseResponse from a dict
get_phone_number_success_response_response_from_dict = GetPhoneNumberSuccessResponseResponse.from_dict(get_phone_number_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


