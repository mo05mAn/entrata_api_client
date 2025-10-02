# GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | ID of the inspection template | 
**name** | **str** | Name of the inspection template | 
**type** | **str** | Type of the inspection template | 
**is_active** | **str** | Indicates if the template is active | 
**allow_actions** | **str** | Indicates if actions are allowed | 
**custom_text** | **str** | Custom text that can be included in the template | 
**terms_and_conditions** | **str** | Terms and conditions for the inspection | 
**property_ids** | **str** | Comma-separated list of property IDs the template applies to | 
**locations** | [**GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocations**](GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInnerLocations.md) |  | 

## Example

```python
from entrata_api_client.models.get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner import GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInner from a JSON string
get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_instance = GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInner.from_json(json)
# print the JSON string representation of the object
print(GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInner.to_json())

# convert the object into a dict
get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_dict = get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_instance.to_dict()
# create an instance of GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInner from a dict
get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_from_dict = GetInspectionTemplatesSuccessResponseResultInspectionTemplatesInspectionTemplateInner.from_dict(get_inspection_templates_success_response_result_inspection_templates_inspection_template_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


