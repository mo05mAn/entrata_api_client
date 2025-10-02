# SendMitsLeadsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**result** | [**SendMitsLeadsSuccessResponseResult**](SendMitsLeadsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_mits_leads_success_response import SendMitsLeadsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendMitsLeadsSuccessResponse from a JSON string
send_mits_leads_success_response_instance = SendMitsLeadsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendMitsLeadsSuccessResponse.to_json())

# convert the object into a dict
send_mits_leads_success_response_dict = send_mits_leads_success_response_instance.to_dict()
# create an instance of SendMitsLeadsSuccessResponse from a dict
send_mits_leads_success_response_from_dict = SendMitsLeadsSuccessResponse.from_dict(send_mits_leads_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


