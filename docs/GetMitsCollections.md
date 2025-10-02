# GetMitsCollections


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetMitsCollectionsMethod**](GetMitsCollectionsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_mits_collections import GetMitsCollections

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsCollections from a JSON string
get_mits_collections_instance = GetMitsCollections.from_json(json)
# print the JSON string representation of the object
print(GetMitsCollections.to_json())

# convert the object into a dict
get_mits_collections_dict = get_mits_collections_instance.to_dict()
# create an instance of GetMitsCollections from a dict
get_mits_collections_from_dict = GetMitsCollections.from_dict(get_mits_collections_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


