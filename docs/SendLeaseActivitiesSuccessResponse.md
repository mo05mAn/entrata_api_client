# SendLeaseActivitiesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**SendLeaseActivitiesSuccessResponseResult**](SendLeaseActivitiesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_lease_activities_success_response import SendLeaseActivitiesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseActivitiesSuccessResponse from a JSON string
send_lease_activities_success_response_instance = SendLeaseActivitiesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendLeaseActivitiesSuccessResponse.to_json())

# convert the object into a dict
send_lease_activities_success_response_dict = send_lease_activities_success_response_instance.to_dict()
# create an instance of SendLeaseActivitiesSuccessResponse from a dict
send_lease_activities_success_response_from_dict = SendLeaseActivitiesSuccessResponse.from_dict(send_lease_activities_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


