# GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours

Operating hours for the property

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**holiday_hours** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHoursHolidayHours**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHoursHolidayHours.md) |  | [optional] 
**office_hours** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHoursOfficeHours**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHoursOfficeHours.md) |  | [optional] 
**pool_hours** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHoursPoolHours**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHoursPoolHours.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_properties_success_response_result_physical_property_property_inner_property_hours import GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours from a JSON string
get_properties_success_response_result_physical_property_property_inner_property_hours_instance = GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours.from_json(json)
# print the JSON string representation of the object
print(GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours.to_json())

# convert the object into a dict
get_properties_success_response_result_physical_property_property_inner_property_hours_dict = get_properties_success_response_result_physical_property_property_inner_property_hours_instance.to_dict()
# create an instance of GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours from a dict
get_properties_success_response_result_physical_property_property_inner_property_hours_from_dict = GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours.from_dict(get_properties_success_response_result_physical_property_property_inner_property_hours_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


