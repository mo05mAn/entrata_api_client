# SendLeaseDocumentsRequestBody

This is required field. This field accept the details of lease, and ducuments being uploaded.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**method** | [**SendLeaseDocumentsRequestBodyMethod**](SendLeaseDocumentsRequestBodyMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_lease_documents_request_body import SendLeaseDocumentsRequestBody

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseDocumentsRequestBody from a JSON string
send_lease_documents_request_body_instance = SendLeaseDocumentsRequestBody.from_json(json)
# print the JSON string representation of the object
print(SendLeaseDocumentsRequestBody.to_json())

# convert the object into a dict
send_lease_documents_request_body_dict = send_lease_documents_request_body_instance.to_dict()
# create an instance of SendLeaseDocumentsRequestBody from a dict
send_lease_documents_request_body_from_dict = SendLeaseDocumentsRequestBody.from_dict(send_lease_documents_request_body_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


