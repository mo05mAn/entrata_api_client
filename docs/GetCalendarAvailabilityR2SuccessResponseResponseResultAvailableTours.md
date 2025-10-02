# GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours

Available tours with their respective timeslots

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**available_tour** | [**List[GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableToursAvailableTourInner]**](GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableToursAvailableTourInner.md) | List of available tours | [optional] 

## Example

```python
from openapi_client.models.get_calendar_availability_r2_success_response_response_result_available_tours import GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours from a JSON string
get_calendar_availability_r2_success_response_response_result_available_tours_instance = GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours.to_json())

# convert the object into a dict
get_calendar_availability_r2_success_response_response_result_available_tours_dict = get_calendar_availability_r2_success_response_response_result_available_tours_instance.to_dict()
# create an instance of GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours from a dict
get_calendar_availability_r2_success_response_response_result_available_tours_from_dict = GetCalendarAvailabilityR2SuccessResponseResponseResultAvailableTours.from_dict(get_calendar_availability_r2_success_response_response_result_available_tours_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


