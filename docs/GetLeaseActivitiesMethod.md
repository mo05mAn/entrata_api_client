# GetLeaseActivitiesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetLeaseActivitiesMethodParams**](GetLeaseActivitiesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_lease_activities_method import GetLeaseActivitiesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseActivitiesMethod from a JSON string
get_lease_activities_method_instance = GetLeaseActivitiesMethod.from_json(json)
# print the JSON string representation of the object
print(GetLeaseActivitiesMethod.to_json())

# convert the object into a dict
get_lease_activities_method_dict = get_lease_activities_method_instance.to_dict()
# create an instance of GetLeaseActivitiesMethod from a dict
get_lease_activities_method_from_dict = GetLeaseActivitiesMethod.from_dict(get_lease_activities_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


