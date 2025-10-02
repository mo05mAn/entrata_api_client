# SendSpecialGroupMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | This is a required field. Property ID for insert Specials | 
**special_group** | [**SendSpecialGroupMethodParamsSpecialGroup**](SendSpecialGroupMethodParamsSpecialGroup.md) |  | 

## Example

```python
from entrata_api_client.models.send_special_group_method_params import SendSpecialGroupMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupMethodParams from a JSON string
send_special_group_method_params_instance = SendSpecialGroupMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupMethodParams.to_json())

# convert the object into a dict
send_special_group_method_params_dict = send_special_group_method_params_instance.to_dict()
# create an instance of SendSpecialGroupMethodParams from a dict
send_special_group_method_params_from_dict = SendSpecialGroupMethodParams.from_dict(send_special_group_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


