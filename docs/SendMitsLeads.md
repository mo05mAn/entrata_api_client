# SendMitsLeads


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendMitsLeadsMethod**](SendMitsLeadsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_mits_leads import SendMitsLeads

# TODO update the JSON string below
json = "{}"
# create an instance of SendMitsLeads from a JSON string
send_mits_leads_instance = SendMitsLeads.from_json(json)
# print the JSON string representation of the object
print(SendMitsLeads.to_json())

# convert the object into a dict
send_mits_leads_dict = send_mits_leads_instance.to_dict()
# create an instance of SendMitsLeads from a dict
send_mits_leads_from_dict = SendMitsLeads.from_dict(send_mits_leads_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


