# UpdateSpecialGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**UpdatePropertyMediaAuth**](UpdatePropertyMediaAuth.md) |  | 
**request_id** | **str** | An arbitrary value to relate with response | [optional] 
**method** | [**UpdateSpecialGroupMethod**](UpdateSpecialGroupMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_special_group import UpdateSpecialGroup

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateSpecialGroup from a JSON string
update_special_group_instance = UpdateSpecialGroup.from_json(json)
# print the JSON string representation of the object
print(UpdateSpecialGroup.to_json())

# convert the object into a dict
update_special_group_dict = update_special_group_instance.to_dict()
# create an instance of UpdateSpecialGroup from a dict
update_special_group_from_dict = UpdateSpecialGroup.from_dict(update_special_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


