# GetCalendarAvailabilityR1MethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. propertyId | 
**from_date** | **date** | This is a required field. This field accepts single value. fromDate indicates from which date we should start to include when ret urning available time periods off the property calendar. Only a 7 da y range is allowed per request and that range includes the fromDate an d toDate in it. | 
**to_date** | **date** | This is a required field. This field accepts single value. toDate indicates up till which date we should include when returning a vailable time periods off the property calendar. Only a 7 day range is allowed per request and that range includes the fromDate and toDate in it. | 
**calendar_event_category_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. Calendar Event type ids. Possible id: 1-General, 2-Resident, 3-Leasing , 4-Maintenance If no Id&#x60;s are passed only Resident and Leasing cat egories are considered by default. | [optional] 

## Example

```python
from entrata_api_client.models.get_calendar_availability_r1_method_params import GetCalendarAvailabilityR1MethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetCalendarAvailabilityR1MethodParams from a JSON string
get_calendar_availability_r1_method_params_instance = GetCalendarAvailabilityR1MethodParams.from_json(json)
# print the JSON string representation of the object
print(GetCalendarAvailabilityR1MethodParams.to_json())

# convert the object into a dict
get_calendar_availability_r1_method_params_dict = get_calendar_availability_r1_method_params_instance.to_dict()
# create an instance of GetCalendarAvailabilityR1MethodParams from a dict
get_calendar_availability_r1_method_params_from_dict = GetCalendarAvailabilityR1MethodParams.from_dict(get_calendar_availability_r1_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


