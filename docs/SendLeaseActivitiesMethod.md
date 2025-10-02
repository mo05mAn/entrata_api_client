# SendLeaseActivitiesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendLeaseActivitiesMethodParams**](SendLeaseActivitiesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_lease_activities_method import SendLeaseActivitiesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseActivitiesMethod from a JSON string
send_lease_activities_method_instance = SendLeaseActivitiesMethod.from_json(json)
# print the JSON string representation of the object
print(SendLeaseActivitiesMethod.to_json())

# convert the object into a dict
send_lease_activities_method_dict = send_lease_activities_method_instance.to_dict()
# create an instance of SendLeaseActivitiesMethod from a dict
send_lease_activities_method_from_dict = SendLeaseActivitiesMethod.from_dict(send_lease_activities_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


