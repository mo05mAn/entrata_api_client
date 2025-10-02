# GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_data** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerTransactionData**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerTransactionData.md) |  | [optional] 
**last_update_date** | **str** | The date when the prospect was last updated. | [optional] 
**customers** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomers**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomers.md) |  | [optional] 
**customer_preferences** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomerPreferences.md) |  | [optional] 
**events** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEvents**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerEvents.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner import GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInner from a JSON string
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_instance = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInner.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInner.to_json())

# convert the object into a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_dict = get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_instance.to_dict()
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInner from a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_from_dict = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInner.from_dict(get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


