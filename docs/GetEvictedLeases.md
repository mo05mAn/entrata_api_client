# GetEvictedLeases


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetEvictedLeasesMethod**](GetEvictedLeasesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_evicted_leases import GetEvictedLeases

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeases from a JSON string
get_evicted_leases_instance = GetEvictedLeases.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeases.to_json())

# convert the object into a dict
get_evicted_leases_dict = get_evicted_leases_instance.to_dict()
# create an instance of GetEvictedLeases from a dict
get_evicted_leases_from_dict = GetEvictedLeases.from_dict(get_evicted_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


