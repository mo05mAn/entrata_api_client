# GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomer


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**List[GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomerIdentificationInner]**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomerIdentificationInner.md) | A list of identification details for the customer. | [optional] 
**name** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomerName**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomerName.md) |  | [optional] 
**phone** | [**GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomerPhone**](GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomerPhone.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customers_customer import GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomer

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomer from a JSON string
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customers_customer_instance = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomer.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomer.to_json())

# convert the object into a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customers_customer_dict = get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customers_customer_instance.to_dict()
# create an instance of GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomer from a dict
get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customers_customer_from_dict = GetMitsLeadsSuccessResponseResultLeadManagementInnerProspectsProspectInnerCustomersCustomer.from_dict(get_mits_leads_success_response_result_lead_management_inner_prospects_prospect_inner_customers_customer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


