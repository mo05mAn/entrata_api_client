# UpdateSpecialGroupMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | Required. Property ID for updating specials | 
**special_group** | [**UpdateSpecialGroupMethodParamsSpecialGroup**](UpdateSpecialGroupMethodParamsSpecialGroup.md) |  | 

## Example

```python
from entrata_api_client.models.update_special_group_method_params import UpdateSpecialGroupMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroupMethodParams from a JSON string
update_special_group_method_params_instance = UpdateSpecialGroupMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroupMethodParams.to_json())

# convert the object into a dict
update_special_group_method_params_dict = update_special_group_method_params_instance.to_dict()
# create an instance of UpdateSpecialGroupMethodParams from a dict
update_special_group_method_params_from_dict = UpdateSpecialGroupMethodParams.from_dict(update_special_group_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


