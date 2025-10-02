# GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**recurring_charge** | [**List[GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner]**](GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesRecurringChargeInner.md) |  | 
**one_time_charge** | [**List[GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner]**](GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesOneTimeChargeInner.md) |  | 
**conditional_charge** | [**List[GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner]**](GetLeaseDetailsR1SuccessResponseResponseResultScheduledChargesConditionalChargeInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_details_r1_success_response_response_result_scheduled_charges import GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges from a JSON string
get_lease_details_r1_success_response_response_result_scheduled_charges_instance = GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges.to_json())

# convert the object into a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_dict = get_lease_details_r1_success_response_response_result_scheduled_charges_instance.to_dict()
# create an instance of GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges from a dict
get_lease_details_r1_success_response_response_result_scheduled_charges_from_dict = GetLeaseDetailsR1SuccessResponseResponseResultScheduledCharges.from_dict(get_lease_details_r1_success_response_response_result_scheduled_charges_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


