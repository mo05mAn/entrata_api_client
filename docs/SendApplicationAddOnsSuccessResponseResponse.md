# SendApplicationAddOnsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary value sent with the request. | 
**code** | **int** | Successful response code. | 
**result** | [**SendApplicationAddOnsSuccessResponseResponseResult**](SendApplicationAddOnsSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_application_add_ons_success_response_response import SendApplicationAddOnsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationAddOnsSuccessResponseResponse from a JSON string
send_application_add_ons_success_response_response_instance = SendApplicationAddOnsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendApplicationAddOnsSuccessResponseResponse.to_json())

# convert the object into a dict
send_application_add_ons_success_response_response_dict = send_application_add_ons_success_response_response_instance.to_dict()
# create an instance of SendApplicationAddOnsSuccessResponseResponse from a dict
send_application_add_ons_success_response_response_from_dict = SendApplicationAddOnsSuccessResponseResponse.from_dict(send_application_add_ons_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


