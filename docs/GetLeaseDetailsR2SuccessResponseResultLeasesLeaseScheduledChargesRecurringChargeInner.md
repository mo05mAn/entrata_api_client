# GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_interval_id** | **str** | Unique identifier for the lease interval. | 
**lease_interval_status** | **str** | Status of the lease interval. | 
**lease_interval_type** | **str** | Type of lease interval. | 
**lease_start_date** | **str** | Start date of the lease interval. | 
**lease_end_date** | **str** | End date of the lease interval. | 

## Example

```python
from entrata_api_client.models.get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_recurring_charge_inner import GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner from a JSON string
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_recurring_charge_inner_instance = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_recurring_charge_inner_dict = get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_recurring_charge_inner_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner from a dict
get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_recurring_charge_inner_from_dict = GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledChargesRecurringChargeInner.from_dict(get_lease_details_r2_success_response_result_leases_lease_scheduled_charges_recurring_charge_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


