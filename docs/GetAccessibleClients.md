# GetAccessibleClients


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetAccessibleClientsMethod**](GetAccessibleClientsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_accessible_clients import GetAccessibleClients

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessibleClients from a JSON string
get_accessible_clients_instance = GetAccessibleClients.from_json(json)
# print the JSON string representation of the object
print(GetAccessibleClients.to_json())

# convert the object into a dict
get_accessible_clients_dict = get_accessible_clients_instance.to_dict()
# create an instance of GetAccessibleClients from a dict
get_accessible_clients_from_dict = GetAccessibleClients.from_dict(get_accessible_clients_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


