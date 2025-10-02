# GetLeaseActivities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeaseActivitiesMethod**](GetLeaseActivitiesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_activities import GetLeaseActivities

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseActivities from a JSON string
get_lease_activities_instance = GetLeaseActivities.from_json(json)
# print the JSON string representation of the object
print(GetLeaseActivities.to_json())

# convert the object into a dict
get_lease_activities_dict = get_lease_activities_instance.to_dict()
# create an instance of GetLeaseActivities from a dict
get_lease_activities_from_dict = GetLeaseActivities.from_dict(get_lease_activities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


