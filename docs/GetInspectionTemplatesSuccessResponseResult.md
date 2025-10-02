# GetInspectionTemplatesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**inspection_templates** | [**GetInspectionTemplatesSuccessResponseResultInspectionTemplates**](GetInspectionTemplatesSuccessResponseResultInspectionTemplates.md) |  | 

## Example

```python
from entrata_api_client.models.get_inspection_templates_success_response_result import GetInspectionTemplatesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionTemplatesSuccessResponseResult from a JSON string
get_inspection_templates_success_response_result_instance = GetInspectionTemplatesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetInspectionTemplatesSuccessResponseResult.to_json())

# convert the object into a dict
get_inspection_templates_success_response_result_dict = get_inspection_templates_success_response_result_instance.to_dict()
# create an instance of GetInspectionTemplatesSuccessResponseResult from a dict
get_inspection_templates_success_response_result_from_dict = GetInspectionTemplatesSuccessResponseResult.from_dict(get_inspection_templates_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


