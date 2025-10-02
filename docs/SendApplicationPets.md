# SendApplicationPets


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendApplicationPetsMethod**](SendApplicationPetsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_application_pets import SendApplicationPets

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationPets from a JSON string
send_application_pets_instance = SendApplicationPets.from_json(json)
# print the JSON string representation of the object
print(SendApplicationPets.to_json())

# convert the object into a dict
send_application_pets_dict = send_application_pets_instance.to_dict()
# create an instance of SendApplicationPets from a dict
send_application_pets_from_dict = SendApplicationPets.from_dict(send_application_pets_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


