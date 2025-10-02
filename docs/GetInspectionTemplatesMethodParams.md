# GetInspectionTemplatesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **str** | This is a required field. This field accepts comma seperated multiple values. The node accepts multiple propertyIds as the input value. | 
**show_disabled** | **int** | This is an optional field. This field accepts single value. The node accepts a boolean value and default value for this node is \&quot;0\&quot;. | [optional] 

## Example

```python
from openapi_client.models.get_inspection_templates_method_params import GetInspectionTemplatesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionTemplatesMethodParams from a JSON string
get_inspection_templates_method_params_instance = GetInspectionTemplatesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetInspectionTemplatesMethodParams.to_json())

# convert the object into a dict
get_inspection_templates_method_params_dict = get_inspection_templates_method_params_instance.to_dict()
# create an instance of GetInspectionTemplatesMethodParams from a dict
get_inspection_templates_method_params_from_dict = GetInspectionTemplatesMethodParams.from_dict(get_inspection_templates_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


