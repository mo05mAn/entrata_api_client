# SendApplicantGeneralDetails


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendApplicantGeneralDetailsMethod**](SendApplicantGeneralDetailsMethod.md) |  | 

## Example

```python
from openapi_client.models.send_applicant_general_details import SendApplicantGeneralDetails

# TODO update the JSON string below
json = "{}"
# create an instance of SendApplicantGeneralDetails from a JSON string
send_applicant_general_details_instance = SendApplicantGeneralDetails.from_json(json)
# print the JSON string representation of the object
print(SendApplicantGeneralDetails.to_json())

# convert the object into a dict
send_applicant_general_details_dict = send_applicant_general_details_instance.to_dict()
# create an instance of SendApplicantGeneralDetails from a dict
send_applicant_general_details_from_dict = SendApplicantGeneralDetails.from_dict(send_applicant_general_details_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


