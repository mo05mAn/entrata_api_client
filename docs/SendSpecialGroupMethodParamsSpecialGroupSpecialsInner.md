# SendSpecialGroupMethodParamsSpecialGroupSpecialsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**special_type_id** | **str** | This is a required field. Special type identifier. | 
**special_name** | **str** | This is a required field. Name of the special. | 
**gift_value** | **str** | This is an optional field. Value of gift type special. | [optional] 
**rates** | [**List[SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner]**](SendSpecialGroupMethodParamsSpecialGroupSpecialsInnerRatesInner.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_special_group_method_params_special_group_specials_inner import SendSpecialGroupMethodParamsSpecialGroupSpecialsInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupMethodParamsSpecialGroupSpecialsInner from a JSON string
send_special_group_method_params_special_group_specials_inner_instance = SendSpecialGroupMethodParamsSpecialGroupSpecialsInner.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupMethodParamsSpecialGroupSpecialsInner.to_json())

# convert the object into a dict
send_special_group_method_params_special_group_specials_inner_dict = send_special_group_method_params_special_group_specials_inner_instance.to_dict()
# create an instance of SendSpecialGroupMethodParamsSpecialGroupSpecialsInner from a dict
send_special_group_method_params_special_group_specials_inner_from_dict = SendSpecialGroupMethodParamsSpecialGroupSpecialsInner.from_dict(send_special_group_method_params_special_group_specials_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


