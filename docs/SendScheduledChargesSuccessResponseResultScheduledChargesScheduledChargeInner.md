# SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the scheduled charge | 
**node** | **str** | Node identifier for the scheduled charge | 
**status** | **str** | Status of the scheduled charge insertion | 
**message** | **str** | Message detailing the result of the scheduled charge insertion | 

## Example

```python
from openapi_client.models.send_scheduled_charges_success_response_result_scheduled_charges_scheduled_charge_inner import SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner from a JSON string
send_scheduled_charges_success_response_result_scheduled_charges_scheduled_charge_inner_instance = SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner.from_json(json)
# print the JSON string representation of the object
print(SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner.to_json())

# convert the object into a dict
send_scheduled_charges_success_response_result_scheduled_charges_scheduled_charge_inner_dict = send_scheduled_charges_success_response_result_scheduled_charges_scheduled_charge_inner_instance.to_dict()
# create an instance of SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner from a dict
send_scheduled_charges_success_response_result_scheduled_charges_scheduled_charge_inner_from_dict = SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner.from_dict(send_scheduled_charges_success_response_result_scheduled_charges_scheduled_charge_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


