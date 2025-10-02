# GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_unit_id** | **str** | The unit identifier. | [optional] 
**unit_number** | **str** | The unit number. | [optional] 
**unit_space_id** | **str** | The unit space identifier. | [optional] 
**unit_type** | **str** | The type of unit desired. | [optional] 
**unit_bedrooms** | **List[str]** |  | [optional] 
**unit_bathrooms** | **List[str]** |  | [optional] 
**min_square_feet** | **List[str]** |  | [optional] 
**max_square_feet** | **List[str]** |  | [optional] 
**initial_rent** | **List[str]** |  | [optional] 
**market_rent** | **List[str]** |  | [optional] 
**max_occupants** | **List[str]** |  | [optional] 
**floorplan_id** | **List[str]** |  | [optional] 
**floorplan_name** | **List[str]** |  | [optional] 
**square_foot_type** | **str** | The type of square footage. | [optional] 
**unit_economic_status** | **str** | The economic status of the unit. | [optional] 
**unit_occupancy_status** | **str** | The occupancy status of the unit. | [optional] 
**unit_leased_status** | **str** | The leased status of the unit. | [optional] 

## Example

```python
from openapi_client.models.get_leads_success_response_result_prospects_prospect_inner_customer_preferences_desired_unit import GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit from a JSON string
get_leads_success_response_result_prospects_prospect_inner_customer_preferences_desired_unit_instance = GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit.to_json())

# convert the object into a dict
get_leads_success_response_result_prospects_prospect_inner_customer_preferences_desired_unit_dict = get_leads_success_response_result_prospects_prospect_inner_customer_preferences_desired_unit_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit from a dict
get_leads_success_response_result_prospects_prospect_inner_customer_preferences_desired_unit_from_dict = GetLeadsSuccessResponseResultProspectsProspectInnerCustomerPreferencesDesiredUnit.from_dict(get_leads_success_response_result_prospects_prospect_inner_customer_preferences_desired_unit_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


