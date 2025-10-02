# SendApplicantGeneralDetailsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendApplicantGeneralDetailsMethodParams**](SendApplicantGeneralDetailsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_applicant_general_details_method import SendApplicantGeneralDetailsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicantGeneralDetailsMethod from a JSON string
send_applicant_general_details_method_instance = SendApplicantGeneralDetailsMethod.from_json(json)
# print the JSON string representation of the object
print(SendApplicantGeneralDetailsMethod.to_json())

# convert the object into a dict
send_applicant_general_details_method_dict = send_applicant_general_details_method_instance.to_dict()
# create an instance of SendApplicantGeneralDetailsMethod from a dict
send_applicant_general_details_method_from_dict = SendApplicantGeneralDetailsMethod.from_dict(send_applicant_general_details_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


