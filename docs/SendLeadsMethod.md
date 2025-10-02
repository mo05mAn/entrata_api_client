# SendLeadsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendLeadsMethodParams**](SendLeadsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_leads_method import SendLeadsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeadsMethod from a JSON string
send_leads_method_instance = SendLeadsMethod.from_json(json)
# print the JSON string representation of the object
print(SendLeadsMethod.to_json())

# convert the object into a dict
send_leads_method_dict = send_leads_method_instance.to_dict()
# create an instance of SendLeadsMethod from a dict
send_leads_method_from_dict = SendLeadsMethod.from_dict(send_leads_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


