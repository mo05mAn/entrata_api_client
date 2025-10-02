# SendApplicationPetsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendApplicationPetsMethodParams**](SendApplicationPetsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_application_pets_method import SendApplicationPetsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationPetsMethod from a JSON string
send_application_pets_method_instance = SendApplicationPetsMethod.from_json(json)
# print the JSON string representation of the object
print(SendApplicationPetsMethod.to_json())

# convert the object into a dict
send_application_pets_method_dict = send_application_pets_method_instance.to_dict()
# create an instance of SendApplicationPetsMethod from a dict
send_application_pets_method_from_dict = SendApplicationPetsMethod.from_dict(send_application_pets_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


