# GetLeasingCenterPickLists


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeasingCenterPickListsMethod**](GetLeasingCenterPickListsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_leasing_center_pick_lists import GetLeasingCenterPickLists

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasingCenterPickLists from a JSON string
get_leasing_center_pick_lists_instance = GetLeasingCenterPickLists.from_json(json)
# print the JSON string representation of the object
print(GetLeasingCenterPickLists.to_json())

# convert the object into a dict
get_leasing_center_pick_lists_dict = get_leasing_center_pick_lists_instance.to_dict()
# create an instance of GetLeasingCenterPickLists from a dict
get_leasing_center_pick_lists_from_dict = GetLeasingCenterPickLists.from_dict(get_leasing_center_pick_lists_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


