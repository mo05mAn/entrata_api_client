# SendScheduledChargesSuccessResponseResultScheduledCharges


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scheduled_charge** | [**List[SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner]**](SendScheduledChargesSuccessResponseResultScheduledChargesScheduledChargeInner.md) |  | 

## Example

```python
from openapi_client.models.send_scheduled_charges_success_response_result_scheduled_charges import SendScheduledChargesSuccessResponseResultScheduledCharges

# TODO update the JSON string below
json = "{}"
# create an instance of SendScheduledChargesSuccessResponseResultScheduledCharges from a JSON string
send_scheduled_charges_success_response_result_scheduled_charges_instance = SendScheduledChargesSuccessResponseResultScheduledCharges.from_json(json)
# print the JSON string representation of the object
print(SendScheduledChargesSuccessResponseResultScheduledCharges.to_json())

# convert the object into a dict
send_scheduled_charges_success_response_result_scheduled_charges_dict = send_scheduled_charges_success_response_result_scheduled_charges_instance.to_dict()
# create an instance of SendScheduledChargesSuccessResponseResultScheduledCharges from a dict
send_scheduled_charges_success_response_result_scheduled_charges_from_dict = SendScheduledChargesSuccessResponseResultScheduledCharges.from_dict(send_scheduled_charges_success_response_result_scheduled_charges_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


