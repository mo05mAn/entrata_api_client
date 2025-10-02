# GetInspectionTemplates


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetInspectionTemplatesMethod**](GetInspectionTemplatesMethod.md) |  | 

## Example

```python
from openapi_client.models.get_inspection_templates import GetInspectionTemplates

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionTemplates from a JSON string
get_inspection_templates_instance = GetInspectionTemplates.from_json(json)
# print the JSON string representation of the object
print(GetInspectionTemplates.to_json())

# convert the object into a dict
get_inspection_templates_dict = get_inspection_templates_instance.to_dict()
# create an instance of GetInspectionTemplates from a dict
get_inspection_templates_from_dict = GetInspectionTemplates.from_dict(get_inspection_templates_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


