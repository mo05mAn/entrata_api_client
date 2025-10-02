# SendLeaseDocumentsRequestBodyMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**lease_id** | **int** | This is an optional field. This field accepts single value. This is the conditionally required, if applicationId and applicantId is not provided. | [optional] 
**application_id** | **int** | This is a optional field. This field accepts single value. This is the conditionally required, if leaseId and applicantId is not provided. | [optional] 
**applicant_id** | **int** | This is a optional field. This field accepts single value. This is conditionally required, if leaseId and applicationId is not provided. | [optional] 
**files** | [**SendLeaseDocumentsRequestBodyMethodParamsFiles**](SendLeaseDocumentsRequestBodyMethodParamsFiles.md) |  | 

## Example

```python
from entrata_api_client.models.send_lease_documents_request_body_method_params import SendLeaseDocumentsRequestBodyMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseDocumentsRequestBodyMethodParams from a JSON string
send_lease_documents_request_body_method_params_instance = SendLeaseDocumentsRequestBodyMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendLeaseDocumentsRequestBodyMethodParams.to_json())

# convert the object into a dict
send_lease_documents_request_body_method_params_dict = send_lease_documents_request_body_method_params_instance.to_dict()
# create an instance of SendLeaseDocumentsRequestBodyMethodParams from a dict
send_lease_documents_request_body_method_params_from_dict = SendLeaseDocumentsRequestBodyMethodParams.from_dict(send_lease_documents_request_body_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


