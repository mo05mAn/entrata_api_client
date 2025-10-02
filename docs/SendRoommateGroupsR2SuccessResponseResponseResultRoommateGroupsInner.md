# SendRoommateGroupsR2SuccessResponseResponseResultRoommateGroupsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Node identifier for the roommate group | 
**roommate_group_id** | **int** | Unique identifier for the roommate group. Returns 0 if creation fails. | 
**status** | **str** | Status of the roommate group creation | 
**message** | **str** | Message detailing the result of the group creation | 

## Example

```python
from openapi_client.models.send_roommate_groups_r2_success_response_response_result_roommate_groups_inner import SendRoommateGroupsR2SuccessResponseResponseResultRoommateGroupsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendRoommateGroupsR2SuccessResponseResponseResultRoommateGroupsInner from a JSON string
send_roommate_groups_r2_success_response_response_result_roommate_groups_inner_instance = SendRoommateGroupsR2SuccessResponseResponseResultRoommateGroupsInner.from_json(json)
# print the JSON string representation of the object
print(SendRoommateGroupsR2SuccessResponseResponseResultRoommateGroupsInner.to_json())

# convert the object into a dict
send_roommate_groups_r2_success_response_response_result_roommate_groups_inner_dict = send_roommate_groups_r2_success_response_response_result_roommate_groups_inner_instance.to_dict()
# create an instance of SendRoommateGroupsR2SuccessResponseResponseResultRoommateGroupsInner from a dict
send_roommate_groups_r2_success_response_response_result_roommate_groups_inner_from_dict = SendRoommateGroupsR2SuccessResponseResponseResultRoommateGroupsInner.from_dict(send_roommate_groups_r2_success_response_response_result_roommate_groups_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


