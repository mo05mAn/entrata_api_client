# GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**recurring_charge** | [**List[GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner]**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner.md) |  | 
**one_time_charge** | [**List[GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner]**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner.md) |  | 
**installment** | [**GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesInstallment.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_lease_details_r2_success_response_result_leases_lease_scheduled_charges import GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges from a JSON string
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_instance = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_dict = get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges from a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_from_dict = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges.from_dict(get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


