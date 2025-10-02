# SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invitor_application_id** | **int** | Required field unless inviteeApplicationId is provided. This field accepts single value. | [optional] 
**invitee_application_id** | [**SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInnerInviteeApplicationId**](SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInnerInviteeApplicationId.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_roommate_groups_r2_method_params_roommate_groups_roommate_group_inner import SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInner from a JSON string
send_roommate_groups_r2_method_params_roommate_groups_roommate_group_inner_instance = SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInner.from_json(json)
# print the JSON string representation of the object
print(SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInner.to_json())

# convert the object into a dict
send_roommate_groups_r2_method_params_roommate_groups_roommate_group_inner_dict = send_roommate_groups_r2_method_params_roommate_groups_roommate_group_inner_instance.to_dict()
# create an instance of SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInner from a dict
send_roommate_groups_r2_method_params_roommate_groups_roommate_group_inner_from_dict = SendRoommateGroupsR2MethodParamsRoommateGroupsRoommateGroupInner.from_dict(send_roommate_groups_r2_method_params_roommate_groups_roommate_group_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


