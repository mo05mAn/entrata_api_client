# GetLeasesR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeasesR1Method**](GetLeasesR1Method.md) |  | 

## Example

```python
from openapi_client.models.get_leases_r1 import GetLeasesR1

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR1 from a JSON string
get_leases_r1_instance = GetLeasesR1.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR1.to_json())

# convert the object into a dict
get_leases_r1_dict = get_leases_r1_instance.to_dict()
# create an instance of GetLeasesR1 from a dict
get_leases_r1_from_dict = GetLeasesR1.from_dict(get_leases_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


