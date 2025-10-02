# UpdateLeadsR2SuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prospects** | [**List[UpdateLeadsR2SuccessResponseResultProspectsInner]**](UpdateLeadsR2SuccessResponseResultProspectsInner.md) | A list of prospects with their status and message. | [optional] 

## Example

```python
from openapi_client.models.update_leads_r2_success_response_result import UpdateLeadsR2SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR2SuccessResponseResult from a JSON string
update_leads_r2_success_response_result_instance = UpdateLeadsR2SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR2SuccessResponseResult.to_json())

# convert the object into a dict
update_leads_r2_success_response_result_dict = update_leads_r2_success_response_result_instance.to_dict()
# create an instance of UpdateLeadsR2SuccessResponseResult from a dict
update_leads_r2_success_response_result_from_dict = UpdateLeadsR2SuccessResponseResult.from_dict(update_leads_r2_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


