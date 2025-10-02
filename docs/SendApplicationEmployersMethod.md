# SendApplicationEmployersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendApplicationEmployersMethodParams**](SendApplicationEmployersMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_application_employers_method import SendApplicationEmployersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationEmployersMethod from a JSON string
send_application_employers_method_instance = SendApplicationEmployersMethod.from_json(json)
# print the JSON string representation of the object
print(SendApplicationEmployersMethod.to_json())

# convert the object into a dict
send_application_employers_method_dict = send_application_employers_method_instance.to_dict()
# create an instance of SendApplicationEmployersMethod from a dict
send_application_employers_method_from_dict = SendApplicationEmployersMethod.from_dict(send_application_employers_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


