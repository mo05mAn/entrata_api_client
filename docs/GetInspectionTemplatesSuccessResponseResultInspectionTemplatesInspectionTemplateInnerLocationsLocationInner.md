# GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**maintenance_location_id** | **str** | ID of the maintenance location | 
**location_name** | **str** | Name of the location | 
**problems** | [**GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInnerProblems**](GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInnerProblems.md) |  | 

## Example

```python
from entrata_api_client.models.get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_locations_location_inner import GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInner from a JSON string
get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_locations_location_inner_instance = GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInner.from_json(json)
# print the JSON string representation of the object
print(GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInner.to_json())

# convert the object into a dict
get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_locations_location_inner_dict = get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_locations_location_inner_instance.to_dict()
# create an instance of GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInner from a dict
get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_locations_location_inner_from_dict = GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocationsLocationInner.from_dict(get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_locations_location_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


