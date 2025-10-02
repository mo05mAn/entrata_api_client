# GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings

Settings related to property calendar

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | Unique identifier for the property | [optional] 
**appointment_length** | **int** | Length of an appointment in minutes | [optional] 
**self_guided_tour_appointment_length** | **int** | Length of a self-guided tour appointment in minutes | [optional] 
**min_lead_time_tour** | **str** | Minimum lead time required for a tour | [optional] 
**self_guided_tour_min_lead_time** | **str** | Minimum lead time for self-guided tours | [optional] 
**availabilities** | [**GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities**](GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities.md) |  | [optional] 
**self_guided_tour_availabilities** | [**GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsSelfGuidedTourAvailabilities**](GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsSelfGuidedTourAvailabilities.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_calendar_availability_r1_success_response_result_property_calendar_settings import GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings from a JSON string
get_calendar_availability_r1_success_response_result_property_calendar_settings_instance = GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings.to_json())

# convert the object into a dict
get_calendar_availability_r1_success_response_result_property_calendar_settings_dict = get_calendar_availability_r1_success_response_result_property_calendar_settings_instance.to_dict()
# create an instance of GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings from a dict
get_calendar_availability_r1_success_response_result_property_calendar_settings_from_dict = GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings.from_dict(get_calendar_availability_r1_success_response_result_property_calendar_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


