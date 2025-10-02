# GetInspectionsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is an optional field. This field accepts single value. | 
**lease_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**unit_space_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**from_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**to_date** | **date** | This is an optional field. This field accepts single value. | [optional] 
**status_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**inspection_form_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**inspection_type_id** | **int** | This is an optional field. This field accepts single value. Supported values are 1( ROUTINE ), 2(MOVE_IN), 3(MOVE_OUT) | [optional] 

## Example

```python
from openapi_client.models.get_inspections_method_params import GetInspectionsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetInspectionsMethodParams from a JSON string
get_inspections_method_params_instance = GetInspectionsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetInspectionsMethodParams.to_json())

# convert the object into a dict
get_inspections_method_params_dict = get_inspections_method_params_instance.to_dict()
# create an instance of GetInspectionsMethodParams from a dict
get_inspections_method_params_from_dict = GetInspectionsMethodParams.from_dict(get_inspections_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


