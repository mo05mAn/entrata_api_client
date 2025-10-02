# GetLeadsSuccessResponseResultProspectsProspectInnerLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_id** | **str** | The lease identifier. | 
**status** | **str** | The status of the lease. | 
**lease_interval_id** | **str** | The lease interval ID. | [optional] 
**expected_move_in_date** | **str** | The expected move-in date. | [optional] 
**expected_move_out_date** | **List[str]** |  | [optional] 
**lease_from_date** | **str** | The date when the lease starts. | 
**lease_to_date** | **List[str]** |  | [optional] 

## Example

```python
from entrata_api_client.models.get_leads_success_response_result_prospects_prospect_inner_lease import GetLeadsSuccessResponseResultProspectsProspectInnerLease

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerLease from a JSON string
get_leads_success_response_result_prospects_prospect_inner_lease_instance = GetLeadsSuccessResponseResultProspectsProspectInnerLease.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResultProspectsProspectInnerLease.to_json())

# convert the object into a dict
get_leads_success_response_result_prospects_prospect_inner_lease_dict = get_leads_success_response_result_prospects_prospect_inner_lease_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerLease from a dict
get_leads_success_response_result_prospects_prospect_inner_lease_from_dict = GetLeadsSuccessResponseResultProspectsProspectInnerLease.from_dict(get_leads_success_response_result_prospects_prospect_inner_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


