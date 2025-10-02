# GetCalendarAvailabilityR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetCalendarAvailabilityR2Method**](GetCalendarAvailabilityR2Method.md) |  | 

## Example

```python
from entrata_api_client.models.get_calendar_availability_r2 import GetCalendarAvailabilityR2

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR2 from a JSON string
get_calendar_availability_r2_instance = GetCalendarAvailabilityR2.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR2.to_json())

# convert the object into a dict
get_calendar_availability_r2_dict = get_calendar_availability_r2_instance.to_dict()
# create an instance of GetCalendarAvailabilityR2 from a dict
get_calendar_availability_r2_from_dict = GetCalendarAvailabilityR2.from_dict(get_calendar_availability_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


