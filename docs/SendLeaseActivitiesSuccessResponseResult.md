# SendLeaseActivitiesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**events** | [**SendLeaseActivitiesSuccessResponseResultEvents**](SendLeaseActivitiesSuccessResponseResultEvents.md) |  | 

## Example

```python
from entrata_api_client.models.send_lease_activities_success_response_result import SendLeaseActivitiesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseActivitiesSuccessResponseResult from a JSON string
send_lease_activities_success_response_result_instance = SendLeaseActivitiesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendLeaseActivitiesSuccessResponseResult.to_json())

# convert the object into a dict
send_lease_activities_success_response_result_dict = send_lease_activities_success_response_result_instance.to_dict()
# create an instance of SendLeaseActivitiesSuccessResponseResult from a dict
send_lease_activities_success_response_result_from_dict = SendLeaseActivitiesSuccessResponseResult.from_dict(send_lease_activities_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


