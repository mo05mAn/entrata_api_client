# UpdateApplicationMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateApplicationMethodParams**](UpdateApplicationMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_application_method import UpdateApplicationMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateApplicationMethod from a JSON string
update_application_method_instance = UpdateApplicationMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateApplicationMethod.to_json())

# convert the object into a dict
update_application_method_dict = update_application_method_instance.to_dict()
# create an instance of UpdateApplicationMethod from a dict
update_application_method_from_dict = UpdateApplicationMethod.from_dict(update_application_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


