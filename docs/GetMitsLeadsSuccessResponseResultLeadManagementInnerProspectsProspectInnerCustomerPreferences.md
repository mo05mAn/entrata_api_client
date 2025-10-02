# GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences

Customer preferences related to the lead.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_move_in_date** | **str** | The target move-in date for the customer. | [optional] 
**desired_lease_terms** | **str** | The desired lease terms. | [optional] 
**desired_lease_term_name** | **str** | The name of the desired lease term. | [optional] 
**amenities** | [**List[GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferencesAmenitiesInner]**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferencesAmenitiesInner.md) | A list of customer amenities. | [optional] 

## Example

```python
from openapi_client.models.get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customer_preferences import GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences from a JSON string
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customer_preferences_instance = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences.to_json())

# convert the object into a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customer_preferences_dict = get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customer_preferences_instance.to_dict()
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences from a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customer_preferences_from_dict = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences.from_dict(get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customer_preferences_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


