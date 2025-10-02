# GetLeadsSuccessResponseResultProspectsProspectInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **str** | The unique identifier for the application. | 
**status** | **str** | The status of the application. | 
**status_id** | **str** | The status identifier. | 
**lead_source_id** | **str** | The lead source identifier. | [optional] 
**lead_source** | **str** | The source of the lead. | [optional] 
**leasing_agent_id** | **str** | The leasing agent identifier. | [optional] 
**leasing_agent** | **str** | The name of the leasing agent. | 
**ps_product_id** | **str** | The product ID for the property or service. | [optional] 
**internet_listing_service_id** | **str** | The identifier of the internet listing service. | [optional] 
**internet_listing_service** | **str** | The internet listing service name. | [optional] 
**last_updated_date** | **str** | The last updated date of the prospect. | [optional] 
**created_on** | **str** | The creation date of the application. | [optional] 
**screening_result_status** | **str** | The result of the screening process. | [optional] 
**space_configuration** | **str** | The configuration of the space requested. | [optional] 
**lease** | [**GetLeadsSuccessResponseResultProspectsProspectInnerLease**](GetLeadsSuccessResponseResultProspectsProspectInnerLease.md) |  | 
**customers** | [**GetLeadsSuccessResponseResultProspectsProspectInnerCustomers**](GetLeadsSuccessResponseResultProspectsProspectInnerCustomers.md) |  | 
**customer_preferences** | [**GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences**](GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences.md) |  | 
**events** | [**GetLeadsSuccessResponseResultProspectsProspectInnerEvents**](GetLeadsSuccessResponseResultProspectsProspectInnerEvents.md) |  | 

## Example

```python
from entrata_api_client.models.get_leads_success_response_result_prospects_prospect_inner import GetLeadsSuccessResponseResultProspectsProspectInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInner from a JSON string
get_leads_success_response_result_prospects_prospect_inner_instance = GetLeadsSuccessResponseResultProspectsProspectInner.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResultProspectsProspectInner.to_json())

# convert the object into a dict
get_leads_success_response_result_prospects_prospect_inner_dict = get_leads_success_response_result_prospects_prospect_inner_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInner from a dict
get_leads_success_response_result_prospects_prospect_inner_from_dict = GetLeadsSuccessResponseResultProspectsProspectInner.from_dict(get_leads_success_response_result_prospects_prospect_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


