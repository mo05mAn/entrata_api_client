# GetCalendarAvailabilityR2SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**GetCalendarAvailabilityR2SuccessResponseResponseResult**](GetCalendarAvailabilityR2SuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_calendar_availability_r2_success_response_response import GetCalendarAvailabilityR2SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR2SuccessResponseResponse from a JSON string
get_calendar_availability_r2_success_response_response_instance = GetCalendarAvailabilityR2SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR2SuccessResponseResponse.to_json())

# convert the object into a dict
get_calendar_availability_r2_success_response_response_dict = get_calendar_availability_r2_success_response_response_instance.to_dict()
# create an instance of GetCalendarAvailabilityR2SuccessResponseResponse from a dict
get_calendar_availability_r2_success_response_response_from_dict = GetCalendarAvailabilityR2SuccessResponseResponse.from_dict(get_calendar_availability_r2_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


