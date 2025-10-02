# SendLeadsSuccessResponseResultProspectsProspectInnerApplicants

Information about the applicants.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**applicant** | [**List[SendLeadsSuccessResponseResultProspectsProspectInnerApplicantsApplicantInner]**](SendLeadsSuccessResponseResultProspectsProspectInnerApplicantsApplicantInner.md) | A list of applicants. | [optional] 

## Example

```python
from entrata_api_client.models.send_leads_success_response_result_prospects_prospect_inner_applicants import SendLeadsSuccessResponseResultProspectsProspectInnerApplicants

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeadsSuccessResponseResultProspectsProspectInnerApplicants from a JSON string
send_leads_success_response_result_prospects_prospect_inner_applicants_instance = SendLeadsSuccessResponseResultProspectsProspectInnerApplicants.from_json(json)
# print the JSON string representation of the object
print(SendLeadsSuccessResponseResultProspectsProspectInnerApplicants.to_json())

# convert the object into a dict
send_leads_success_response_result_prospects_prospect_inner_applicants_dict = send_leads_success_response_result_prospects_prospect_inner_applicants_instance.to_dict()
# create an instance of SendLeadsSuccessResponseResultProspectsProspectInnerApplicants from a dict
send_leads_success_response_result_prospects_prospect_inner_applicants_from_dict = SendLeadsSuccessResponseResultProspectsProspectInnerApplicants.from_dict(send_leads_success_response_result_prospects_prospect_inner_applicants_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


