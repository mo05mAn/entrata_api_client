# SendApplicationEmployersSuccessResponseResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**employers** | [**SendApplicationEmployersSuccessResponseResponseResultEmployers**](SendApplicationEmployersSuccessResponseResponseResultEmployers.md) |  | 

## Example

```python
from entrata_api_client.models.send_application_employers_success_response_response_result import SendApplicationEmployersSuccessResponseResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationEmployersSuccessResponseResponseResult from a JSON string
send_application_employers_success_response_response_result_instance = SendApplicationEmployersSuccessResponseResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendApplicationEmployersSuccessResponseResponseResult.to_json())

# convert the object into a dict
send_application_employers_success_response_response_result_dict = send_application_employers_success_response_response_result_instance.to_dict()
# create an instance of SendApplicationEmployersSuccessResponseResponseResult from a dict
send_application_employers_success_response_response_result_from_dict = SendApplicationEmployersSuccessResponseResponseResult.from_dict(send_application_employers_success_response_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


