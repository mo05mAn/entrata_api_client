# SendRoommateGroupsR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | An arbitrary value to relate with response. | [optional] 
**method** | [**SendRoommateGroupsR2Method**](SendRoommateGroupsR2Method.md) |  | 

## Example

```python
from openapi_client.models.send_roommate_groups_r2 import SendRoommateGroupsR2

# TODO update the JSON string below
json = "{}"
# create an instance of SendRoommateGroupsR2 from a JSON string
send_roommate_groups_r2_instance = SendRoommateGroupsR2.from_json(json)
# print the JSON string representation of the object
print(SendRoommateGroupsR2.to_json())

# convert the object into a dict
send_roommate_groups_r2_dict = send_roommate_groups_r2_instance.to_dict()
# create an instance of SendRoommateGroupsR2 from a dict
send_roommate_groups_r2_from_dict = SendRoommateGroupsR2.from_dict(send_roommate_groups_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


