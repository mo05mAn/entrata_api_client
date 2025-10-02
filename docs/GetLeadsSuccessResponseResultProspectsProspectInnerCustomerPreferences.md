# GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**target_move_in_date** | **str** | The target move-in date. | [optional] 
**desired_floorplan** | **str** | The desired floorplan. | [optional] 
**desired_unit** | [**GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit**](GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit.md) |  | [optional] 
**desired_min_rent** | **str** | The desired minimum rent. | [optional] 
**desired_max_rent** | **str** | The desired maximum rent. | [optional] 
**desired_num_bedrooms** | **List[str]** |  | [optional] 
**desired_num_bathrooms** | **List[str]** |  | [optional] 
**desired_lease_terms** | **str** | The desired lease terms. | [optional] 
**desired_lease_term_name** | **str** | The name of the lease term. | [optional] 
**number_of_occupants** | **str** | The number of occupants. | [optional] 
**amenities** | [**GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesAmenities**](GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesAmenities.md) |  | [optional] 
**pets** | [**GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesPets**](GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesPets.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_leads_success_response_result_prospects_prospect_inner_customer_preferences import GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences from a JSON string
get_leads_success_response_result_prospects_prospect_inner_customer_preferences_instance = GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences.to_json())

# convert the object into a dict
get_leads_success_response_result_prospects_prospect_inner_customer_preferences_dict = get_leads_success_response_result_prospects_prospect_inner_customer_preferences_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences from a dict
get_leads_success_response_result_prospects_prospect_inner_customer_preferences_from_dict = GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferences.from_dict(get_leads_success_response_result_prospects_prospect_inner_customer_preferences_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


