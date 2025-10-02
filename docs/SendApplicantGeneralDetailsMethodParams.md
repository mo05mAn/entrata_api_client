# SendApplicantGeneralDetailsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**application_id** | **int** | This is a required field. This field accepts single value. | 
**property_id** | **int** | This is a required field. This field accepts single value. | 
**applicant_id** | **int** | This is a required field. This field accepts single value. | 
**id** | **int** | This is a required field. This field accepts single value. | 
**is_true** | **int** |  | [optional] 
**comments** | **str** | This is a required field. This field accepts single value. | [optional] 

## Example

```python
from openapi_client.models.send_applicant_general_details_method_params import SendApplicantGeneralDetailsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicantGeneralDetailsMethodParams from a JSON string
send_applicant_general_details_method_params_instance = SendApplicantGeneralDetailsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendApplicantGeneralDetailsMethodParams.to_json())

# convert the object into a dict
send_applicant_general_details_method_params_dict = send_applicant_general_details_method_params_instance.to_dict()
# create an instance of SendApplicantGeneralDetailsMethodParams from a dict
send_applicant_general_details_method_params_from_dict = SendApplicantGeneralDetailsMethodParams.from_dict(send_applicant_general_details_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


