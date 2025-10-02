# SendScheduledChargesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scheduled_charges** | [**SendScheduledChargesSuccessResponseResultScheduledCharges**](SendScheduledChargesSuccessResponseResultScheduledCharges.md) |  | 

## Example

```python
from openapi_client.models.send_scheduled_charges_success_response_result import SendScheduledChargesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendScheduledChargesSuccessResponseResult from a JSON string
send_scheduled_charges_success_response_result_instance = SendScheduledChargesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendScheduledChargesSuccessResponseResult.to_json())

# convert the object into a dict
send_scheduled_charges_success_response_result_dict = send_scheduled_charges_success_response_result_instance.to_dict()
# create an instance of SendScheduledChargesSuccessResponseResult from a dict
send_scheduled_charges_success_response_result_from_dict = SendScheduledChargesSuccessResponseResult.from_dict(send_scheduled_charges_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


