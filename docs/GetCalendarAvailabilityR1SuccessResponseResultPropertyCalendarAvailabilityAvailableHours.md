# GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHours

List of available hours for specific dates

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**available_hour** | [**List[GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHoursAvailableHourInner]**](GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHoursAvailableHourInner.md) | List of available hours | [optional] 

## Example

```python
from openapi_client.models.get_calendar_availability_r1_success_response_result_property_calendar_availability_available_hours import GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHours

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHours from a JSON string
get_calendar_availability_r1_success_response_result_property_calendar_availability_available_hours_instance = GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHours.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHours.to_json())

# convert the object into a dict
get_calendar_availability_r1_success_response_result_property_calendar_availability_available_hours_dict = get_calendar_availability_r1_success_response_result_property_calendar_availability_available_hours_instance.to_dict()
# create an instance of GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHours from a dict
get_calendar_availability_r1_success_response_result_property_calendar_availability_available_hours_from_dict = GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailabilityAvailableHours.from_dict(get_calendar_availability_r1_success_response_result_property_calendar_availability_available_hours_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


