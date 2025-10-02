# UpdateApplicationSuccessResponseResponseResultApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the application. | 
**message** | **str** | Message indicating the application update result. | 
**application_id** | **int** | Unique ID of the application. | 
**applicant_ids** | **str** | Comma-separated list of applicant IDs. | 

## Example

```python
from entrata_api_client.models.update_application_success_response_response_result_application import UpdateApplicationSuccessResponseResponseResultApplication

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateApplicationSuccessResponseResponseResultApplication from a JSON string
update_application_success_response_response_result_application_instance = UpdateApplicationSuccessResponseResponseResultApplication.from_json(json)
# print the JSON string representation of the object
print(UpdateApplicationSuccessResponseResponseResultApplication.to_json())

# convert the object into a dict
update_application_success_response_response_result_application_dict = update_application_success_response_response_result_application_instance.to_dict()
# create an instance of UpdateApplicationSuccessResponseResponseResultApplication from a dict
update_application_success_response_response_result_application_from_dict = UpdateApplicationSuccessResponseResponseResultApplication.from_dict(update_application_success_response_response_result_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


