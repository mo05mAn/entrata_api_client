# GetWebsitesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetWebsitesMethodParams**](GetWebsitesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_websites_method import GetWebsitesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetWebsitesMethod from a JSON string
get_websites_method_instance = GetWebsitesMethod.from_json(json)
# print the JSON string representation of the object
print(GetWebsitesMethod.to_json())

# convert the object into a dict
get_websites_method_dict = get_websites_method_instance.to_dict()
# create an instance of GetWebsitesMethod from a dict
get_websites_method_from_dict = GetWebsitesMethod.from_dict(get_websites_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


