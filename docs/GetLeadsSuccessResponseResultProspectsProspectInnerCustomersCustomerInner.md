# GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **str** | The customer identifier. | 
**name_prefix** | **str** | The prefix for the customer&#39;s name. | 
**first_name** | **str** | The first name of the customer. | 
**middle_name** | **str** | The middle name of the customer. | [optional] 
**last_name** | **str** | The last name of the customer. | 
**maiden_name** | **str** | The maiden name of the customer. | [optional] 
**name_suffix** | **str** | The suffix for the customer&#39;s name. | [optional] 
**personal_phone_number** | **str** | The personal phone number of the customer. | [optional] 
**cell_phone_number** | **str** | The cell phone number of the customer. | [optional] 
**office_phone_number** | **str** | The office phone number of the customer. | [optional] 
**fax_phone_number** | **str** | The fax number of the customer. | [optional] 
**email** | **str** | The email address of the customer. | [optional] 
**birth_date** | **str** | The birthdate of the customer. | [optional] 
**addresses** | [**GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInnerAddresses**](GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInnerAddresses.md) |  | [optional] 
**is_active_bankruptcy** | **bool** | The Bankruptcy status of customer . | [optional] 
**bankruptcy_date** | **str** | The Bankruptcy date of customer. | [optional] 
**bankruptcy_note** | **str** | XYZ | [optional] 

## Example

```python
from openapi_client.models.get_leads_success_response_result_prospects_prospect_inner_customers_customer_inner import GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInner from a JSON string
get_leads_success_response_result_prospects_prospect_inner_customers_customer_inner_instance = GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInner.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInner.to_json())

# convert the object into a dict
get_leads_success_response_result_prospects_prospect_inner_customers_customer_inner_dict = get_leads_success_response_result_prospects_prospect_inner_customers_customer_inner_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInner from a dict
get_leads_success_response_result_prospects_prospect_inner_customers_customer_inner_from_dict = GetLeadsSuccessResponseResultProspectsProspectInnerCustomersCustomerInner.from_dict(get_leads_success_response_result_prospects_prospect_inner_customers_customer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


