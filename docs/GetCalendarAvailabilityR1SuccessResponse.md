# GetCalendarAvailabilityR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Success response code | 
**result** | [**GetCalendarAvailabilityR1SuccessResponseResult**](GetCalendarAvailabilityR1SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_calendar_availability_r1_success_response import GetCalendarAvailabilityR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR1SuccessResponse from a JSON string
get_calendar_availability_r1_success_response_instance = GetCalendarAvailabilityR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR1SuccessResponse.to_json())

# convert the object into a dict
get_calendar_availability_r1_success_response_dict = get_calendar_availability_r1_success_response_instance.to_dict()
# create an instance of GetCalendarAvailabilityR1SuccessResponse from a dict
get_calendar_availability_r1_success_response_from_dict = GetCalendarAvailabilityR1SuccessResponse.from_dict(get_calendar_availability_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


