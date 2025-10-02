# GetMitsLeases


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetMitsLeasesMethod**](GetMitsLeasesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_mits_leases import GetMitsLeases

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeases from a JSON string
get_mits_leases_instance = GetMitsLeases.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeases.to_json())

# convert the object into a dict
get_mits_leases_dict = get_mits_leases_instance.to_dict()
# create an instance of GetMitsLeases from a dict
get_mits_leases_from_dict = GetMitsLeases.from_dict(get_mits_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


