# SendApplicantGeneralDetailsSuccessResponseResponseResultInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | The status of the response. | 
**message** | **str** | Message indicating the general details were updated successfully. | 
**applicant_id** | **str** | The unique identifier for the applicant. | 

## Example

```python
from entrata_api_client.models.send_applicant_general_details_success_response_response_result_inner import SendApplicantGeneralDetailsSuccessResponseResponseResultInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicantGeneralDetailsSuccessResponseResponseResultInner from a JSON string
send_applicant_general_details_success_response_response_result_inner_instance = SendApplicantGeneralDetailsSuccessResponseResponseResultInner.from_json(json)
# print the JSON string representation of the object
print(SendApplicantGeneralDetailsSuccessResponseResponseResultInner.to_json())

# convert the object into a dict
send_applicant_general_details_success_response_response_result_inner_dict = send_applicant_general_details_success_response_response_result_inner_instance.to_dict()
# create an instance of SendApplicantGeneralDetailsSuccessResponseResponseResultInner from a dict
send_applicant_general_details_success_response_response_result_inner_from_dict = SendApplicantGeneralDetailsSuccessResponseResponseResultInner.from_dict(send_applicant_general_details_success_response_response_result_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


