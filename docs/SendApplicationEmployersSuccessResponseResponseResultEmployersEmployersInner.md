# SendApplicationEmployersSuccessResponseResponseResultEmployersEmployersInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Success | 
**message** | **str** | Customer employers saved successfully. | 
**id** | **int** | Employer ID. | 
**customer_id** | **int** | Customer ID. | 
**income_type_id** | **int** | Income type ID. | 
**node** | **int** | Node number. | 

## Example

```python
from openapi_client.models.send_application_employers_success_response_response_result_employers_employers_inner import SendApplicationEmployersSuccessResponseResponseResultEmployersEmployersInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicationEmployersSuccessResponseResponseResultEmployersEmployersInner from a JSON string
send_application_employers_success_response_response_result_employers_employers_inner_instance = SendApplicationEmployersSuccessResponseResponseResultEmployersEmployersInner.from_json(json)
# print the JSON string representation of the object
print(SendApplicationEmployersSuccessResponseResponseResultEmployersEmployersInner.to_json())

# convert the object into a dict
send_application_employers_success_response_response_result_employers_employers_inner_dict = send_application_employers_success_response_response_result_employers_employers_inner_instance.to_dict()
# create an instance of SendApplicationEmployersSuccessResponseResponseResultEmployersEmployersInner from a dict
send_application_employers_success_response_response_result_employers_employers_inner_from_dict = SendApplicationEmployersSuccessResponseResponseResultEmployersEmployersInner.from_dict(send_application_employers_success_response_response_result_employers_employers_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


