# SendMitsLeadsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendMitsLeadsMethodParams**](SendMitsLeadsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_mits_leads_method import SendMitsLeadsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendMitsLeadsMethod from a JSON string
send_mits_leads_method_instance = SendMitsLeadsMethod.from_json(json)
# print the JSON string representation of the object
print(SendMitsLeadsMethod.to_json())

# convert the object into a dict
send_mits_leads_method_dict = send_mits_leads_method_instance.to_dict()
# create an instance of SendMitsLeadsMethod from a dict
send_mits_leads_method_from_dict = SendMitsLeadsMethod.from_dict(send_mits_leads_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


