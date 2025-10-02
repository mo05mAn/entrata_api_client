# GetInspectionsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetInspectionsMethodParams**](GetInspectionsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_inspections_method import GetInspectionsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionsMethod from a JSON string
get_inspections_method_instance = GetInspectionsMethod.from_json(json)
# print the JSON string representation of the object
print(GetInspectionsMethod.to_json())

# convert the object into a dict
get_inspections_method_dict = get_inspections_method_instance.to_dict()
# create an instance of GetInspectionsMethod from a dict
get_inspections_method_from_dict = GetInspectionsMethod.from_dict(get_inspections_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


