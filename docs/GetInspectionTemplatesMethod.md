# GetInspectionTemplatesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetInspectionTemplatesMethodParams**](GetInspectionTemplatesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_inspection_templates_method import GetInspectionTemplatesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionTemplatesMethod from a JSON string
get_inspection_templates_method_instance = GetInspectionTemplatesMethod.from_json(json)
# print the JSON string representation of the object
print(GetInspectionTemplatesMethod.to_json())

# convert the object into a dict
get_inspection_templates_method_dict = get_inspection_templates_method_instance.to_dict()
# create an instance of GetInspectionTemplatesMethod from a dict
get_inspection_templates_method_from_dict = GetInspectionTemplatesMethod.from_dict(get_inspection_templates_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


