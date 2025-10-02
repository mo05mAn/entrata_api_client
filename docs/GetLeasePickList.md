# GetLeasePickList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeasePickListMethod**](GetLeasePickListMethod.md) |  | 

## Example

```python
from openapi_client.models.get_lease_pick_list import GetLeasePickList

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasePickList from a JSON string
get_lease_pick_list_instance = GetLeasePickList.from_json(json)
# print the JSON string representation of the object
print(GetLeasePickList.to_json())

# convert the object into a dict
get_lease_pick_list_dict = get_lease_pick_list_instance.to_dict()
# create an instance of GetLeasePickList from a dict
get_lease_pick_list_from_dict = GetLeasePickList.from_dict(get_lease_pick_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


