# SendLeadsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response code indicating the result. | 
**result** | [**SendLeadsSuccessResponseResult**](SendLeadsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_leads_success_response import SendLeadsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeadsSuccessResponse from a JSON string
send_leads_success_response_instance = SendLeadsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendLeadsSuccessResponse.to_json())

# convert the object into a dict
send_leads_success_response_dict = send_leads_success_response_instance.to_dict()
# create an instance of SendLeadsSuccessResponse from a dict
send_leads_success_response_from_dict = SendLeadsSuccessResponse.from_dict(send_leads_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


