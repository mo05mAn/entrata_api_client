# GetLeadEventsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response code indicating the result. | 
**result** | [**GetLeadEventsSuccessResponseResult**](GetLeadEventsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_lead_events_success_response import GetLeadEventsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEventsSuccessResponse from a JSON string
get_lead_events_success_response_instance = GetLeadEventsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeadEventsSuccessResponse.to_json())

# convert the object into a dict
get_lead_events_success_response_dict = get_lead_events_success_response_instance.to_dict()
# create an instance of GetLeadEventsSuccessResponse from a dict
get_lead_events_success_response_from_dict = GetLeadEventsSuccessResponse.from_dict(get_lead_events_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


