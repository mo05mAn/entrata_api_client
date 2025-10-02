# GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_interval_status** | **str** | The status of the lease interval. | 
**lease_interval_type** | **str** | Type of lease interval. | 
**active_scheduled_charges** | [**GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInnerActiveScheduledCharges**](GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInnerActiveScheduledCharges.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_success_response_response_result_scheduled_charges_recurring_charge_inner import GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner from a JSON string
get_lease_details_r1_success_response_response_result_scheduled_charges_recurring_charge_inner_instance = GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_recurring_charge_inner_dict = get_lease_details_r1_success_response_response_result_scheduled_charges_recurring_charge_inner_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner from a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_recurring_charge_inner_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner.from_dict(get_lease_details_r1_success_response_response_result_scheduled_charges_recurring_charge_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


