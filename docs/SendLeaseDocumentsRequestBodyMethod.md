# SendLeaseDocumentsRequestBodyMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendLeaseDocumentsRequestBodyMethodParams**](SendLeaseDocumentsRequestBodyMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_lease_documents_request_body_method import SendLeaseDocumentsRequestBodyMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseDocumentsRequestBodyMethod from a JSON string
send_lease_documents_request_body_method_instance = SendLeaseDocumentsRequestBodyMethod.from_json(json)
# print the JSON string representation of the object
print(SendLeaseDocumentsRequestBodyMethod.to_json())

# convert the object into a dict
send_lease_documents_request_body_method_dict = send_lease_documents_request_body_method_instance.to_dict()
# create an instance of SendLeaseDocumentsRequestBodyMethod from a dict
send_lease_documents_request_body_method_from_dict = SendLeaseDocumentsRequestBodyMethod.from_dict(send_lease_documents_request_body_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


