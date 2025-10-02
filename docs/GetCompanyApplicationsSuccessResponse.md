# GetCompanyApplicationsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetCompanyApplicationsSuccessResponseResponse**](GetCompanyApplicationsSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.get_company_applications_success_response import GetCompanyApplicationsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetCompanyApplicationsSuccessResponse from a JSON string
get_company_applications_success_response_instance = GetCompanyApplicationsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetCompanyApplicationsSuccessResponse.to_json())

# convert the object into a dict
get_company_applications_success_response_dict = get_company_applications_success_response_instance.to_dict()
# create an instance of GetCompanyApplicationsSuccessResponse from a dict
get_company_applications_success_response_from_dict = GetCompanyApplicationsSuccessResponse.from_dict(get_company_applications_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


