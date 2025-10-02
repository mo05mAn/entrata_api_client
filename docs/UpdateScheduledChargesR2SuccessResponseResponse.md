# UpdateScheduledChargesR2SuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Successful response code. | 
**result** | [**UpdateScheduledChargesR2SuccessResponseResponseResult**](UpdateScheduledChargesR2SuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_scheduled_charges_r2_success_response_response import UpdateScheduledChargesR2SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateScheduledChargesR2SuccessResponseResponse from a JSON string
update_scheduled_charges_r2_success_response_response_instance = UpdateScheduledChargesR2SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateScheduledChargesR2SuccessResponseResponse.to_json())

# convert the object into a dict
update_scheduled_charges_r2_success_response_response_dict = update_scheduled_charges_r2_success_response_response_instance.to_dict()
# create an instance of UpdateScheduledChargesR2SuccessResponseResponse from a dict
update_scheduled_charges_r2_success_response_response_from_dict = UpdateScheduledChargesR2SuccessResponseResponse.from_dict(update_scheduled_charges_r2_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


