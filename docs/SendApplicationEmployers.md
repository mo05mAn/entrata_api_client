# SendApplicationEmployers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendApplicationEmployersMethod**](SendApplicationEmployersMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_application_employers import SendApplicationEmployers

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationEmployers from a JSON string
send_application_employers_instance = SendApplicationEmployers.from_json(json)
# print the JSON string representation of the object
print(SendApplicationEmployers.to_json())

# convert the object into a dict
send_application_employers_dict = send_application_employers_instance.to_dict()
# create an instance of SendApplicationEmployers from a dict
send_application_employers_from_dict = SendApplicationEmployers.from_dict(send_application_employers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


