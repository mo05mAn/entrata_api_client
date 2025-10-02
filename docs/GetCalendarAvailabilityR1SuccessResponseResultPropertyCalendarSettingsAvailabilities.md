# GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities

Availability schedule for the property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**availability** | [**List[GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilitiesAvailabilityInner]**](GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilitiesAvailabilityInner.md) | List of availability slots | [optional] 

## Example

```python
from openapi_client.models.get_calendar_availability_r1_success_response_result_property_calendar_settings_availabilities import GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities from a JSON string
get_calendar_availability_r1_success_response_result_property_calendar_settings_availabilities_instance = GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities.to_json())

# convert the object into a dict
get_calendar_availability_r1_success_response_result_property_calendar_settings_availabilities_dict = get_calendar_availability_r1_success_response_result_property_calendar_settings_availabilities_instance.to_dict()
# create an instance of GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities from a dict
get_calendar_availability_r1_success_response_result_property_calendar_settings_availabilities_from_dict = GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettingsAvailabilities.from_dict(get_calendar_availability_r1_success_response_result_property_calendar_settings_availabilities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


