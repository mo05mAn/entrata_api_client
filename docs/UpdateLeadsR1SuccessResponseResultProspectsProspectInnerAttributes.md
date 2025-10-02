# UpdateLeadsR1SuccessResponseResultProspectsProspectInnerAttributes

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
from openapi_client.models.update_leads_r1_success_response_result_prospects_prospect_inner_attributes import UpdateLeadsR1SuccessResponseResultProspectsProspectInnerAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR1SuccessResponseResultProspectsProspectInnerAttributes from a JSON string
update_leads_r1_success_response_result_prospects_prospect_inner_attributes_instance = UpdateLeadsR1SuccessResponseResultProspectsProspectInnerAttributes.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR1SuccessResponseResultProspectsProspectInnerAttributes.to_json())

# convert the object into a dict
update_leads_r1_success_response_result_prospects_prospect_inner_attributes_dict = update_leads_r1_success_response_result_prospects_prospect_inner_attributes_instance.to_dict()
# create an instance of UpdateLeadsR1SuccessResponseResultProspectsProspectInnerAttributes from a dict
update_leads_r1_success_response_result_prospects_prospect_inner_attributes_from_dict = UpdateLeadsR1SuccessResponseResultProspectsProspectInnerAttributes.from_dict(update_leads_r1_success_response_result_prospects_prospect_inner_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


