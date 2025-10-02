# SendScheduledChargesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**SendScheduledChargesSuccessResponseResult**](SendScheduledChargesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_scheduled_charges_success_response import SendScheduledChargesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendScheduledChargesSuccessResponse from a JSON string
send_scheduled_charges_success_response_instance = SendScheduledChargesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendScheduledChargesSuccessResponse.to_json())

# convert the object into a dict
send_scheduled_charges_success_response_dict = send_scheduled_charges_success_response_instance.to_dict()
# create an instance of SendScheduledChargesSuccessResponse from a dict
send_scheduled_charges_success_response_from_dict = SendScheduledChargesSuccessResponse.from_dict(send_scheduled_charges_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


