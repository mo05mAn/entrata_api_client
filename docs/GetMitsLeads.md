# GetMitsLeads


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetMitsLeadsMethod**](GetMitsLeadsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_mits_leads import GetMitsLeads

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeads from a JSON string
get_mits_leads_instance = GetMitsLeads.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeads.to_json())

# convert the object into a dict
get_mits_leads_dict = get_mits_leads_instance.to_dict()
# create an instance of GetMitsLeads from a dict
get_mits_leads_from_dict = GetMitsLeads.from_dict(get_mits_leads_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


