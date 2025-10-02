# GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | Unique identifier for the property | 
**parent_property_id** | **int** | Parent property identifier | [optional] 
**marketing_name** | **str** | Marketing name of the property | 
**type** | **str** | Type of the property (e.g., Apartment) | 
**general_id** | **str** | General identifier for the property | [optional] 
**year_built** | **str** | Year the property was built | 
**short_description** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerShortDescription**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerShortDescription.md) |  | 
**long_description** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerLongDescription**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerLongDescription.md) |  | 
**web_site** | **str** | Website URL for the property | 
**address** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerAddress.md) |  | 
**post_months** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPostMonths**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPostMonths.md) |  | 
**is_disabled** | **str** | Indicates if the property is disabled | 
**is_featured_property** | **str** | Indicates if the property is featured | 
**custom_keys_data** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerCustomKeysData**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerCustomKeysData.md) |  | [optional] 
**property_hours** | [**GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours**](GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInnerPropertyHours.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_properties_success_response_result_physical_property_property_inner import GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner from a JSON string
get_properties_success_response_result_physical_property_property_inner_instance = GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner.from_json(json)
# print the JSON string representation of the object
print(GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner.to_json())

# convert the object into a dict
get_properties_success_response_result_physical_property_property_inner_dict = get_properties_success_response_result_physical_property_property_inner_instance.to_dict()
# create an instance of GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner from a dict
get_properties_success_response_result_physical_property_property_inner_from_dict = GetPropertiesSuccessResponseResultPhysicalPropertyPropertyInner.from_dict(get_properties_success_response_result_physical_property_property_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


