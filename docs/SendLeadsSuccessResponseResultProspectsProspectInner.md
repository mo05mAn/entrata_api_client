# SendLeadsSuccessResponseResultProspectsProspectInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | A node identifier for the prospect. | [optional] 
**application_id** | **str** | The unique identifier for the application. | [optional] 
**applicant_id** | **str** | The unique identifier for the applicant. | [optional] 
**status** | **str** | The status of the prospect. | [optional] 
**message** | **str** | A message associated with the prospect. | [optional] 
**applicants** | [**SendLeadsSuccessResponseResultProspectsProspectInnerApplicants**](SendLeadsSuccessResponseResultProspectsProspectInnerApplicants.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_leads_success_response_result_prospects_prospect_inner import SendLeadsSuccessResponseResultProspectsProspectInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeadsSuccessResponseResultProspectsProspectInner from a JSON string
send_leads_success_response_result_prospects_prospect_inner_instance = SendLeadsSuccessResponseResultProspectsProspectInner.from_json(json)
# print the JSON string representation of the object
print(SendLeadsSuccessResponseResultProspectsProspectInner.to_json())

# convert the object into a dict
send_leads_success_response_result_prospects_prospect_inner_dict = send_leads_success_response_result_prospects_prospect_inner_instance.to_dict()
# create an instance of SendLeadsSuccessResponseResultProspectsProspectInner from a dict
send_leads_success_response_result_prospects_prospect_inner_from_dict = SendLeadsSuccessResponseResultProspectsProspectInner.from_dict(send_leads_success_response_result_prospects_prospect_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


