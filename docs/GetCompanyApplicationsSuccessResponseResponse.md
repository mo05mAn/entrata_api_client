# GetCompanyApplicationsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary value sent with the request. | [optional] 
**code** | **int** | Successful response code | 
**result** | [**GetCompanyApplicationsSuccessResponseResponseResult**](GetCompanyApplicationsSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_company_applications_success_response_response import GetCompanyApplicationsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetCompanyApplicationsSuccessResponseResponse from a JSON string
get_company_applications_success_response_response_instance = GetCompanyApplicationsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetCompanyApplicationsSuccessResponseResponse.to_json())

# convert the object into a dict
get_company_applications_success_response_response_dict = get_company_applications_success_response_response_instance.to_dict()
# create an instance of GetCompanyApplicationsSuccessResponseResponse from a dict
get_company_applications_success_response_response_from_dict = GetCompanyApplicationsSuccessResponseResponse.from_dict(get_company_applications_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


