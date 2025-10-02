# GetLeadPickListsR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeadPickListsR1Method**](GetLeadPickListsR1Method.md) |  | 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r1 import GetLeadPickListsR1

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR1 from a JSON string
get_lead_pick_lists_r1_instance = GetLeadPickListsR1.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR1.to_json())

# convert the object into a dict
get_lead_pick_lists_r1_dict = get_lead_pick_lists_r1_instance.to_dict()
# create an instance of GetLeadPickListsR1 from a dict
get_lead_pick_lists_r1_from_dict = GetLeadPickListsR1.from_dict(get_lead_pick_lists_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


