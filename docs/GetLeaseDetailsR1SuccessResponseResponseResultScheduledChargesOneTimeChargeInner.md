# GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_interval_status** | **str** | The status of the lease interval. | 
**lease_interval_type** | **str** | Type of lease interval. | 
**active_scheduled_charges** | [**GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInnerActiveScheduledCharges**](GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInnerActiveScheduledCharges.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_success_response_response_result_scheduled_charges_one_time_charge_inner import GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner from a JSON string
get_lease_details_r1_success_response_response_result_scheduled_charges_one_time_charge_inner_instance = GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_one_time_charge_inner_dict = get_lease_details_r1_success_response_response_result_scheduled_charges_one_time_charge_inner_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner from a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_one_time_charge_inner_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner.from_dict(get_lease_details_r1_success_response_response_result_scheduled_charges_one_time_charge_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


