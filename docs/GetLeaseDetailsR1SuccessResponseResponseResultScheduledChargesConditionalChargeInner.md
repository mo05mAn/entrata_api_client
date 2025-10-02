# GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_interval_status** | **str** | The status of the lease interval. | 
**lease_interval_type** | **str** | Type of lease interval. | 
**active_scheduled_charges** | [**GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInnerActiveScheduledCharges**](GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInnerActiveScheduledCharges.md) |  | 

## Example

```python
from openapi_client.models.get_lease_details_r1_success_response_response_result_scheduled_charges_conditional_charge_inner import GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner from a JSON string
get_lease_details_r1_success_response_response_result_scheduled_charges_conditional_charge_inner_instance = GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_conditional_charge_inner_dict = get_lease_details_r1_success_response_response_result_scheduled_charges_conditional_charge_inner_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner from a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_conditional_charge_inner_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner.from_dict(get_lease_details_r1_success_response_response_result_scheduled_charges_conditional_charge_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


