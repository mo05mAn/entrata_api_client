# GetCalendarAvailabilityR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetCalendarAvailabilityR1Method**](GetCalendarAvailabilityR1Method.md) |  | 

## Example

```python
from openapi_client.models.get_calendar_availability_r1 import GetCalendarAvailabilityR1

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR1 from a JSON string
get_calendar_availability_r1_instance = GetCalendarAvailabilityR1.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR1.to_json())

# convert the object into a dict
get_calendar_availability_r1_dict = get_calendar_availability_r1_instance.to_dict()
# create an instance of GetCalendarAvailabilityR1 from a dict
get_calendar_availability_r1_from_dict = GetCalendarAvailabilityR1.from_dict(get_calendar_availability_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


