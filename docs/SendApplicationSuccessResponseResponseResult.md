# SendApplicationSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The status of the response. | 
**message** | **str** | A message indicating the application was inserted successfully. | 
**applicant_id** | **str** | The unique identifier for the applicant. | 
**applicant_ids** | **str** | A comma-separated list of applicant IDs. | [optional] 

## Example

```python
from entrata_api_client.models.send_application_success_response_response_result import SendApplicationSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationSuccessResponseResponseResult from a JSON string
send_application_success_response_response_result_instance = SendApplicationSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendApplicationSuccessResponseResponseResult.to_json())

# convert the object into a dict
send_application_success_response_response_result_dict = send_application_success_response_response_result_instance.to_dict()
# create an instance of SendApplicationSuccessResponseResponseResult from a dict
send_application_success_response_response_result_from_dict = SendApplicationSuccessResponseResponseResult.from_dict(send_application_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


