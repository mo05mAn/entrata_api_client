# GetCompanyApplications


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetCompanyApplicationsMethod**](GetCompanyApplicationsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_company_applications import GetCompanyApplications

# TODO update the JSON string below
json = "{}"
# create an instance of GetCompanyApplications from a JSON string
get_company_applications_instance = GetCompanyApplications.from_json(json)
# print the JSON string representation of the object
print(GetCompanyApplications.to_json())

# convert the object into a dict
get_company_applications_dict = get_company_applications_instance.to_dict()
# create an instance of GetCompanyApplications from a dict
get_company_applications_from_dict = GetCompanyApplications.from_dict(get_company_applications_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


