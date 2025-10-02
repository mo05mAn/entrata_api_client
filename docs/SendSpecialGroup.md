# SendSpecialGroup


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**UpdatePropertyMediaAuth**](UpdatePropertyMediaAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendSpecialGroupMethod**](SendSpecialGroupMethod.md) |  | 

## Example

```python
from openapi_client.models.send_special_group import SendSpecialGroup

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroup from a JSON string
send_special_group_instance = SendSpecialGroup.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroup.to_json())

# convert the object into a dict
send_special_group_dict = send_special_group_instance.to_dict()
# create an instance of SendSpecialGroup from a dict
send_special_group_from_dict = SendSpecialGroup.from_dict(send_special_group_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


