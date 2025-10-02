# GetCompanyApplicationsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 

## Example

```python
from entrata_api_client.models.get_company_applications_method_params import GetCompanyApplicationsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetCompanyApplicationsMethodParams from a JSON string
get_company_applications_method_params_instance = GetCompanyApplicationsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetCompanyApplicationsMethodParams.to_json())

# convert the object into a dict
get_company_applications_method_params_dict = get_company_applications_method_params_instance.to_dict()
# create an instance of GetCompanyApplicationsMethodParams from a dict
get_company_applications_method_params_from_dict = GetCompanyApplicationsMethodParams.from_dict(get_company_applications_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


