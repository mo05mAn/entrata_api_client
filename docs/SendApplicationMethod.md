# SendApplicationMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendApplicationMethodParams**](SendApplicationMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_application_method import SendApplicationMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationMethod from a JSON string
send_application_method_instance = SendApplicationMethod.from_json(json)
# print the JSON string representation of the object
print(SendApplicationMethod.to_json())

# convert the object into a dict
send_application_method_dict = send_application_method_instance.to_dict()
# create an instance of SendApplicationMethod from a dict
send_application_method_from_dict = SendApplicationMethod.from_dict(send_application_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


