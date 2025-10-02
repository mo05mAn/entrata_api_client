# GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_code_id** | **str** | The AR code identifier. | 
**charge_code** | **str** | Code for the charge. | 
**charge_timing** | **str** | When the charge is applied. | 
**charge_usage** | **str** | Usage type of the charge. | 
**charge_start_date** | **str** | Start date of the charge. | 
**charge_end_date** | **str** | End date of the charge. | [optional] 
**charge_amount** | **str** | Amount for the charge. | 

## Example

```python
from entrata_api_client.models.get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_charge import GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge from a JSON string
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_charge_instance = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_charge_dict = get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_charge_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge from a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_charge_from_dict = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge.from_dict(get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_charge_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


