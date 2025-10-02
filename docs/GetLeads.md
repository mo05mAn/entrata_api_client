# GetLeads


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeadsMethod**](GetLeadsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_leads import GetLeads

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeads from a JSON string
get_leads_instance = GetLeads.from_json(json)
# print the JSON string representation of the object
print(GetLeads.to_json())

# convert the object into a dict
get_leads_dict = get_leads_instance.to_dict()
# create an instance of GetLeads from a dict
get_leads_from_dict = GetLeads.from_dict(get_leads_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


