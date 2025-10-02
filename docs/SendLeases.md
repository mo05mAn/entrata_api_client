# SendLeases


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendLeasesMethod**](SendLeasesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_leases import SendLeases

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeases from a JSON string
send_leases_instance = SendLeases.from_json(json)
# print the JSON string representation of the object
print(SendLeases.to_json())

# convert the object into a dict
send_leases_dict = send_leases_instance.to_dict()
# create an instance of SendLeases from a dict
send_leases_from_dict = SendLeases.from_dict(send_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


