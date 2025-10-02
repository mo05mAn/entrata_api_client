# GetCalendarAvailabilityR1SuccessResponseResult

The result containing property calendar details

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_calendar_settings** | [**GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings**](GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarSettings.md) |  | [optional] 
**property_calendar_availability** | [**GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailability**](GetCalendarAvailabilityR1SuccessResponseResultPropertyCalendarAvailability.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_calendar_availability_r1_success_response_result import GetCalendarAvailabilityR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR1SuccessResponseResult from a JSON string
get_calendar_availability_r1_success_response_result_instance = GetCalendarAvailabilityR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR1SuccessResponseResult.to_json())

# convert the object into a dict
get_calendar_availability_r1_success_response_result_dict = get_calendar_availability_r1_success_response_result_instance.to_dict()
# create an instance of GetCalendarAvailabilityR1SuccessResponseResult from a dict
get_calendar_availability_r1_success_response_result_from_dict = GetCalendarAvailabilityR1SuccessResponseResult.from_dict(get_calendar_availability_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


