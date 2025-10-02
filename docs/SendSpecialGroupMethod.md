# SendSpecialGroupMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | 
**params** | [**SendSpecialGroupMethodParams**](SendSpecialGroupMethodParams.md) |  | 

## Example

```python
from openapi_client.models.send_special_group_method import SendSpecialGroupMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendSpecialGroupMethod from a JSON string
send_special_group_method_instance = SendSpecialGroupMethod.from_json(json)
# print the JSON string representation of the object
print(SendSpecialGroupMethod.to_json())

# convert the object into a dict
send_special_group_method_dict = send_special_group_method_instance.to_dict()
# create an instance of SendSpecialGroupMethod from a dict
send_special_group_method_from_dict = SendSpecialGroupMethod.from_dict(send_special_group_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


