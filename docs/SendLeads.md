# SendLeads


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendLeadsMethod**](SendLeadsMethod.md) |  | 

## Example

```python
from openapi_client.models.send_leads import SendLeads

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeads from a JSON string
send_leads_instance = SendLeads.from_json(json)
# print the JSON string representation of the object
print(SendLeads.to_json())

# convert the object into a dict
send_leads_dict = send_leads_instance.to_dict()
# create an instance of SendLeads from a dict
send_leads_from_dict = SendLeads.from_dict(send_leads_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


