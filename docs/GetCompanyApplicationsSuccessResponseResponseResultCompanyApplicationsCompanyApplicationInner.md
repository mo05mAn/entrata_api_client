# GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**company_application_id** | **str** | The unique identifier for the company application. | 
**company_application_name** | **str** | The name of the company application. | 
**application_questions** | [**List[GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInnerApplicationQuestionsInner]**](GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInnerApplicationQuestionsInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_company_applications_success_response_response_result_company_applications_company_application_inner import GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInner from a JSON string
get_company_applications_success_response_response_result_company_applications_company_application_inner_instance = GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInner.from_json(json)
# print the JSON string representation of the object
print(GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInner.to_json())

# convert the object into a dict
get_company_applications_success_response_response_result_company_applications_company_application_inner_dict = get_company_applications_success_response_response_result_company_applications_company_application_inner_instance.to_dict()
# create an instance of GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInner from a dict
get_company_applications_success_response_response_result_company_applications_company_application_inner_from_dict = GetCompanyApplicationsSuccessResponseResponseResultCompanyApplicationsCompanyApplicationInner.from_dict(get_company_applications_success_response_response_result_company_applications_company_application_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


