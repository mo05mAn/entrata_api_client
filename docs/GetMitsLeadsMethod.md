# GetMitsLeadsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetMitsLeadsMethodParams**](GetMitsLeadsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_leads_method import GetMitsLeadsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsMethod from a JSON string
get_mits_leads_method_instance = GetMitsLeadsMethod.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsMethod.to_json())

# convert the object into a dict
get_mits_leads_method_dict = get_mits_leads_method_instance.to_dict()
# create an instance of GetMitsLeadsMethod from a dict
get_mits_leads_method_from_dict = GetMitsLeadsMethod.from_dict(get_mits_leads_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


