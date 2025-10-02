# UpdateScheduledChargesR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**UpdateScheduledChargesR1SuccessResponseResult**](UpdateScheduledChargesR1SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_scheduled_charges_r1_success_response import UpdateScheduledChargesR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateScheduledChargesR1SuccessResponse from a JSON string
update_scheduled_charges_r1_success_response_instance = UpdateScheduledChargesR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateScheduledChargesR1SuccessResponse.to_json())

# convert the object into a dict
update_scheduled_charges_r1_success_response_dict = update_scheduled_charges_r1_success_response_instance.to_dict()
# create an instance of UpdateScheduledChargesR1SuccessResponse from a dict
update_scheduled_charges_r1_success_response_from_dict = UpdateScheduledChargesR1SuccessResponse.from_dict(update_scheduled_charges_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


