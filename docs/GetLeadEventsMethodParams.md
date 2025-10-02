# GetLeadEventsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**application_id** | **int** | This is an optional field. This field accepts single value. Conditionally required, If eventTypeIds and eventDates are not passed then applicationId is required. | [optional] 
**event_type_ids** | **str** | This is an optional field. This field accepts single value. | [optional] 
**event_date_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**event_date_to** | **date** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_events_method_params import GetLeadEventsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEventsMethodParams from a JSON string
get_lead_events_method_params_instance = GetLeadEventsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetLeadEventsMethodParams.to_json())

# convert the object into a dict
get_lead_events_method_params_dict = get_lead_events_method_params_instance.to_dict()
# create an instance of GetLeadEventsMethodParams from a dict
get_lead_events_method_params_from_dict = GetLeadEventsMethodParams.from_dict(get_lead_events_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


