# GetLeaseActivitiesSuccessResponseResponseResultEventsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event_id** | **int** | Unique identifier for the event | 
**type_id** | **int** | Type identifier for the event | 
**lease_id** | **int** | ID of the associated lease | 
**lease_interval_id** | **int** | ID of the lease interval | 
**type** | **str** | Type of the event | 
**subtype_id** | **int** | Subtype identifier for the event | [optional] 
**get_data_reference_id** | **int** | Reference ID for getting data | 
**var_date** | **str** | Date of the event | 
**comments** | **str** | Comments about the event | [optional] 
**event_reasons** | **str** | Reasons for the event | [optional] 
**call_data** | [**GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData**](GetLeaseActivitiesSuccessResponseResponseResultEventsInnerCallData.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_activities_success_response_response_result_events_inner import GetLeaseActivitiesSuccessResponseResponseResultEventsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseActivitiesSuccessResponseResponseResultEventsInner from a JSON string
get_lease_activities_success_response_response_result_events_inner_instance = GetLeaseActivitiesSuccessResponseResponseResultEventsInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseActivitiesSuccessResponseResponseResultEventsInner.to_json())

# convert the object into a dict
get_lease_activities_success_response_response_result_events_inner_dict = get_lease_activities_success_response_response_result_events_inner_instance.to_dict()
# create an instance of GetLeaseActivitiesSuccessResponseResponseResultEventsInner from a dict
get_lease_activities_success_response_response_result_events_inner_from_dict = GetLeaseActivitiesSuccessResponseResponseResultEventsInner.from_dict(get_lease_activities_success_response_response_result_events_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


