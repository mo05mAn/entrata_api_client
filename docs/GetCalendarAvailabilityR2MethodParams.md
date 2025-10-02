# GetCalendarAvailabilityR2MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**from_date** | **date** | This is a required field. This field accepts single value. fromDate indicates from which date we should start to include when ret urning available time periods off the property calendar. Only a 60 d ay range is allowed per request and that range includes the fromDate and toDate in it. | 
**to_date** | **date** | This is a required field. This field accepts single value. toDate indicates up till which date we should include when returning a vailable time periods off the property calendar. Only a 60 day range is allowed per request and that range includes the fromDate and toDate in it. | 
**tour_type** | **str** | This is a required field. This field accepts single value. tour type: SELF_GUIDED, VIRTUAL_GUIDED,AGENT_GUIDED | [optional] 

## Example

```python
from entrata_api_client.models.get_calendar_availability_r2_method_params import GetCalendarAvailabilityR2MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR2MethodParams from a JSON string
get_calendar_availability_r2_method_params_instance = GetCalendarAvailabilityR2MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR2MethodParams.to_json())

# convert the object into a dict
get_calendar_availability_r2_method_params_dict = get_calendar_availability_r2_method_params_instance.to_dict()
# create an instance of GetCalendarAvailabilityR2MethodParams from a dict
get_calendar_availability_r2_method_params_from_dict = GetCalendarAvailabilityR2MethodParams.from_dict(get_calendar_availability_r2_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


