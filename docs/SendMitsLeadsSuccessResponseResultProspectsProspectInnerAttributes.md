# SendMitsLeadsSuccessResponseResultProspectsProspectInnerAttributes

Attributes related to the prospect.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | A node identifier for the prospect. | [optional] 
**reference_id** | **str** | The unique identifier for the reference. | [optional] 
**applicant_id** | **str** | The unique identifier for the applicant. | [optional] 
**status** | **str** | The status of the prospect. | [optional] 
**message** | **str** | A message associated with the prospect. | [optional] 

## Example

```python
from openapi_client.models.send_mits_leads_success_response_result_prospects_prospect_inner_attributes import SendMitsLeadsSuccessResponseResultProspectsProspectInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of SendMitsLeadsSuccessResponseResultProspectsProspectInnerAttributes from a JSON string
send_mits_leads_success_response_result_prospects_prospect_inner_attributes_instance = SendMitsLeadsSuccessResponseResultProspectsProspectInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(SendMitsLeadsSuccessResponseResultProspectsProspectInnerAttributes.to_json())

# convert the object into a dict
send_mits_leads_success_response_result_prospects_prospect_inner_attributes_dict = send_mits_leads_success_response_result_prospects_prospect_inner_attributes_instance.to_dict()
# create an instance of SendMitsLeadsSuccessResponseResultProspectsProspectInnerAttributes from a dict
send_mits_leads_success_response_result_prospects_prospect_inner_attributes_from_dict = SendMitsLeadsSuccessResponseResultProspectsProspectInnerAttributes.from_dict(send_mits_leads_success_response_result_prospects_prospect_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


