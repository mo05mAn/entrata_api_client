# GetEvictedLeasesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetEvictedLeasesMethodParams**](GetEvictedLeasesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_evicted_leases_method import GetEvictedLeasesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesMethod from a JSON string
get_evicted_leases_method_instance = GetEvictedLeasesMethod.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesMethod.to_json())

# convert the object into a dict
get_evicted_leases_method_dict = get_evicted_leases_method_instance.to_dict()
# create an instance of GetEvictedLeasesMethod from a dict
get_evicted_leases_method_from_dict = GetEvictedLeasesMethod.from_dict(get_evicted_leases_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


