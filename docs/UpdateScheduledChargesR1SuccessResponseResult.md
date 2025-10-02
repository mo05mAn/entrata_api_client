# UpdateScheduledChargesR1SuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**scheduled_charges** | [**UpdateScheduledChargesR1SuccessResponseResultScheduledCharges**](UpdateScheduledChargesR1SuccessResponseResultScheduledCharges.md) |  | 

## Example

```python
from entrata_api_client.models.update_scheduled_charges_r1_success_response_result import UpdateScheduledChargesR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateScheduledChargesR1SuccessResponseResult from a JSON string
update_scheduled_charges_r1_success_response_result_instance = UpdateScheduledChargesR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateScheduledChargesR1SuccessResponseResult.to_json())

# convert the object into a dict
update_scheduled_charges_r1_success_response_result_dict = update_scheduled_charges_r1_success_response_result_instance.to_dict()
# create an instance of UpdateScheduledChargesR1SuccessResponseResult from a dict
update_scheduled_charges_r1_success_response_result_from_dict = UpdateScheduledChargesR1SuccessResponseResult.from_dict(update_scheduled_charges_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


