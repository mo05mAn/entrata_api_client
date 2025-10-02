# SendAmenitiesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**SendAmenitiesSuccessResponseResponse**](SendAmenitiesSuccessResponseResponse.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_amenities_success_response import SendAmenitiesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenitiesSuccessResponse from a JSON string
send_amenities_success_response_instance = SendAmenitiesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendAmenitiesSuccessResponse.to_json())

# convert the object into a dict
send_amenities_success_response_dict = send_amenities_success_response_instance.to_dict()
# create an instance of SendAmenitiesSuccessResponse from a dict
send_amenities_success_response_from_dict = SendAmenitiesSuccessResponse.from_dict(send_amenities_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


