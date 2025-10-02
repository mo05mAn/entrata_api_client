# SendLeaseActivities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendLeaseActivitiesMethod**](SendLeaseActivitiesMethod.md) |  | 

## Example

```python
from openapi_client.models.send_lease_activities import SendLeaseActivities

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseActivities from a JSON string
send_lease_activities_instance = SendLeaseActivities.from_json(json)
# print the JSON string representation of the object
print(SendLeaseActivities.to_json())

# convert the object into a dict
send_lease_activities_dict = send_lease_activities_instance.to_dict()
# create an instance of SendLeaseActivities from a dict
send_lease_activities_from_dict = SendLeaseActivities.from_dict(send_lease_activities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


