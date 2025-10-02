# GetLeadsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetLeadsMethodParams**](GetLeadsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_leads_method import GetLeadsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsMethod from a JSON string
get_leads_method_instance = GetLeadsMethod.from_json(json)
# print the JSON string representation of the object
print(GetLeadsMethod.to_json())

# convert the object into a dict
get_leads_method_dict = get_leads_method_instance.to_dict()
# create an instance of GetLeadsMethod from a dict
get_leads_method_from_dict = GetLeadsMethod.from_dict(get_leads_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


