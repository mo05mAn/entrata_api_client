# GetLeasesR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeasesR2Method**](GetLeasesR2Method.md) |  | 

## Example

```python
from openapi_client.models.get_leases_r2 import GetLeasesR2

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR2 from a JSON string
get_leases_r2_instance = GetLeasesR2.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR2.to_json())

# convert the object into a dict
get_leases_r2_dict = get_leases_r2_instance.to_dict()
# create an instance of GetLeasesR2 from a dict
get_leases_r2_from_dict = GetLeasesR2.from_dict(get_leases_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


