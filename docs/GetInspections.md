# GetInspections


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetInspectionsMethod**](GetInspectionsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_inspections import GetInspections

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspections from a JSON string
get_inspections_instance = GetInspections.from_json(json)
# print the JSON string representation of the object
print(GetInspections.to_json())

# convert the object into a dict
get_inspections_dict = get_inspections_instance.to_dict()
# create an instance of GetInspections from a dict
get_inspections_from_dict = GetInspections.from_dict(get_inspections_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


