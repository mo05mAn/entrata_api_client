# GetWebsitesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **int** | This is a required field. This field accepts comma seperated multiple values. PropertyIds | 

## Example

```python
from openapi_client.models.get_websites_method_params import GetWebsitesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetWebsitesMethodParams from a JSON string
get_websites_method_params_instance = GetWebsitesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetWebsitesMethodParams.to_json())

# convert the object into a dict
get_websites_method_params_dict = get_websites_method_params_instance.to_dict()
# create an instance of GetWebsitesMethodParams from a dict
get_websites_method_params_from_dict = GetWebsitesMethodParams.from_dict(get_websites_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


