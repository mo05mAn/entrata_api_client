# SendLeadsSuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prospects** | [**SendLeadsSuccessResponseResultProspects**](SendLeadsSuccessResponseResultProspects.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_leads_success_response_result import SendLeadsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeadsSuccessResponseResult from a JSON string
send_leads_success_response_result_instance = SendLeadsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendLeadsSuccessResponseResult.to_json())

# convert the object into a dict
send_leads_success_response_result_dict = send_leads_success_response_result_instance.to_dict()
# create an instance of SendLeadsSuccessResponseResult from a dict
send_leads_success_response_result_from_dict = SendLeadsSuccessResponseResult.from_dict(send_leads_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


