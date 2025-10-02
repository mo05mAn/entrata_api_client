# SendApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendApplicationMethod**](SendApplicationMethod.md) |  | 

## Example

```python
from openapi_client.models.send_application import SendApplication

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplication from a JSON string
send_application_instance = SendApplication.from_json(json)
# print the JSON string representation of the object
print(SendApplication.to_json())

# convert the object into a dict
send_application_dict = send_application_instance.to_dict()
# create an instance of SendApplication from a dict
send_application_from_dict = SendApplication.from_dict(send_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


