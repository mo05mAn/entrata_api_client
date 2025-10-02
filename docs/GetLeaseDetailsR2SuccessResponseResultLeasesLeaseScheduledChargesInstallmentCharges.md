# GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**charge** | [**GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesCharge.md) |  | 
**active_scheduled_charges** | [**GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesActiveScheduledCharges**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesActiveScheduledCharges.md) |  | [optional] 
**past_scheduled_charges** | [**GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesPastScheduledCharges**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentChargesPastScheduledCharges.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges import GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges from a JSON string
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_instance = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_dict = get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges from a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_from_dict = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges.from_dict(get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_charges_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


