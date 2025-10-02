# GetCalendarAvailabilityR2SuccessResponseResponseResult

The result containing available tours and their timeslots

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**available_tours** | [**GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours**](GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_calendar_availability_r2_success_response_response_result import GetCalendarAvailabilityR2SuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR2SuccessResponseResponseResult from a JSON string
get_calendar_availability_r2_success_response_response_result_instance = GetCalendarAvailabilityR2SuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR2SuccessResponseResponseResult.to_json())

# convert the object into a dict
get_calendar_availability_r2_success_response_response_result_dict = get_calendar_availability_r2_success_response_response_result_instance.to_dict()
# create an instance of GetCalendarAvailabilityR2SuccessResponseResponseResult from a dict
get_calendar_availability_r2_success_response_response_result_from_dict = GetCalendarAvailabilityR2SuccessResponseResponseResult.from_dict(get_calendar_availability_r2_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


