# UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**special_id** | **str** | Required. ID of the special | 
**special_type_id** | **str** | Required. Type ID of the special | 
**special_name** | **str** | Required. Name of the special | 
**gift_value** | **str** | Optional. Value for gift type specials | [optional] 
**is_delete** | **int** | Optional. pass this field if only wants to delete the special. otherwise do not pass this field. | [optional] 
**rates** | [**List[UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner]**](UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_special_group_method_params_special_group_specials_inner import UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner from a JSON string
update_special_group_method_params_special_group_specials_inner_instance = UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner.to_json())

# convert the object into a dict
update_special_group_method_params_special_group_specials_inner_dict = update_special_group_method_params_special_group_specials_inner_instance.to_dict()
# create an instance of UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner from a dict
update_special_group_method_params_special_group_specials_inner_from_dict = UpdateSpecialGroupMethodParamsSpecialGroupSpecialsInner.from_dict(update_special_group_method_params_special_group_specials_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


