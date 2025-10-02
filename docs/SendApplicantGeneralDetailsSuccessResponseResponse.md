# SendApplicantGeneralDetailsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | An arbitrary value sent with the request. | [optional] 
**code** | **int** | Successful response code. | 
**result** | [**List[SendApplicantGeneralDetailsSuccessResponseResponseResultInner]**](SendApplicantGeneralDetailsSuccessResponseResponseResultInner.md) |  | 

## Example

```python
from openapi_client.models.send_applicant_general_details_success_response_response import SendApplicantGeneralDetailsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicantGeneralDetailsSuccessResponseResponse from a JSON string
send_applicant_general_details_success_response_response_instance = SendApplicantGeneralDetailsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(SendApplicantGeneralDetailsSuccessResponseResponse.to_json())

# convert the object into a dict
send_applicant_general_details_success_response_response_dict = send_applicant_general_details_success_response_response_instance.to_dict()
# create an instance of SendApplicantGeneralDetailsSuccessResponseResponse from a dict
send_applicant_general_details_success_response_response_from_dict = SendApplicantGeneralDetailsSuccessResponseResponse.from_dict(send_applicant_general_details_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


