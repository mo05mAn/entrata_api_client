# GetCompanyApplicationsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetCompanyApplicationsMethodParams**](GetCompanyApplicationsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_company_applications_method import GetCompanyApplicationsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetCompanyApplicationsMethod from a JSON string
get_company_applications_method_instance = GetCompanyApplicationsMethod.from_json(json)
# print the JSON string representation of the object
print(GetCompanyApplicationsMethod.to_json())

# convert the object into a dict
get_company_applications_method_dict = get_company_applications_method_instance.to_dict()
# create an instance of GetCompanyApplicationsMethod from a dict
get_company_applications_method_from_dict = GetCompanyApplicationsMethod.from_dict(get_company_applications_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


