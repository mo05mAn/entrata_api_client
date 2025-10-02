# GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**installment_name** | **str** | Name of the installment. | 
**installment_start_date** | **str** | Start date of the installment. | 
**installment_end_date** | **str** | End date of the installment. | 
**charges** | [**GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallmentCharges.md) |  | 

## Example

```python
from openapi_client.models.get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment import GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment from a JSON string
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_instance = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_dict = get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment from a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_from_dict = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment.from_dict(get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_installment_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


