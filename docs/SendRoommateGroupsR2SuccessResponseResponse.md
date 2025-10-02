# SendRoommateGroupsR2SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response code | 
**result** | [**SendRoommateGroupsR2SuccessResponseResponseResult**](SendRoommateGroupsR2SuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.send_roommate_groups_r2_success_response_response import SendRoommateGroupsR2SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendRoommateGroupsR2SuccessResponseResponse from a JSON string
send_roommate_groups_r2_success_response_response_instance = SendRoommateGroupsR2SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendRoommateGroupsR2SuccessResponseResponse.to_json())

# convert the object into a dict
send_roommate_groups_r2_success_response_response_dict = send_roommate_groups_r2_success_response_response_instance.to_dict()
# create an instance of SendRoommateGroupsR2SuccessResponseResponse from a dict
send_roommate_groups_r2_success_response_response_from_dict = SendRoommateGroupsR2SuccessResponseResponse.from_dict(send_roommate_groups_r2_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


