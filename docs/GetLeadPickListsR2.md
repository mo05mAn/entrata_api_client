# GetLeadPickListsR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeadPickListsR2Method**](GetLeadPickListsR2Method.md) |  | 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r2 import GetLeadPickListsR2

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2 from a JSON string
get_lead_pick_lists_r2_instance = GetLeadPickListsR2.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_dict = get_lead_pick_lists_r2_instance.to_dict()
# create an instance of GetLeadPickListsR2 from a dict
get_lead_pick_lists_r2_from_dict = GetLeadPickListsR2.from_dict(get_lead_pick_lists_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


