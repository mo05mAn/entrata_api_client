# SendAmenitiesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**SendAmenitiesSuccessResponseResponseResult**](SendAmenitiesSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_amenities_success_response_response import SendAmenitiesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenitiesSuccessResponseResponse from a JSON string
send_amenities_success_response_response_instance = SendAmenitiesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendAmenitiesSuccessResponseResponse.to_json())

# convert the object into a dict
send_amenities_success_response_response_dict = send_amenities_success_response_response_instance.to_dict()
# create an instance of SendAmenitiesSuccessResponseResponse from a dict
send_amenities_success_response_response_from_dict = SendAmenitiesSuccessResponseResponse.from_dict(send_amenities_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


