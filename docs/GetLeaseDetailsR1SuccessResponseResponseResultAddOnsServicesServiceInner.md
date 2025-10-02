# GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServicesServiceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**add_on_type** | **str** | Type of the service. | 
**add_on_category** | **str** | Category of the service. | 
**add_on_group** | **str** | Group the service belongs to. | [optional] 
**add_on_name** | **str** | Name of the service. | 
**lease_status_type** | **str** | Lease status of the service. | 
**start_date** | **str** | Start date of the service. | 
**end_date** | **str** | End date of the service. | 
**agent** | **str** | Agent responsible for the service. | 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_success_response_response_result_add_ons_services_service_inner import GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServicesServiceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServicesServiceInner from a JSON string
get_lease_details_r1_success_response_response_result_add_ons_services_service_inner_instance = GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServicesServiceInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServicesServiceInner.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_add_ons_services_service_inner_dict = get_lease_details_r1_success_response_response_result_add_ons_services_service_inner_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServicesServiceInner from a dict
get_lease_details_r1_success_response_response_result_add_ons_services_service_inner_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultAddOnsServicesServiceInner.from_dict(get_lease_details_r1_success_response_response_result_add_ons_services_service_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


