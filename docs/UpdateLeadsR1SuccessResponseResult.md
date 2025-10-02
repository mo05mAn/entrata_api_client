# UpdateLeadsR1SuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prospects** | [**UpdateLeadsR1SuccessResponseResultProspects**](UpdateLeadsR1SuccessResponseResultProspects.md) |  | [optional] 

## Example

```python
from openapi_client.models.update_leads_r1_success_response_result import UpdateLeadsR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR1SuccessResponseResult from a JSON string
update_leads_r1_success_response_result_instance = UpdateLeadsR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR1SuccessResponseResult.to_json())

# convert the object into a dict
update_leads_r1_success_response_result_dict = update_leads_r1_success_response_result_instance.to_dict()
# create an instance of UpdateLeadsR1SuccessResponseResult from a dict
update_leads_r1_success_response_result_from_dict = UpdateLeadsR1SuccessResponseResult.from_dict(update_leads_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


