# GetLeaseDocumentsListSuccessResponseResultLeaseDocuments


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_document** | [**List[GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner]**](GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner.md) |  | 

## Example

```python
from openapi_client.models.get_lease_documents_list_success_response_result_lease_documents import GetLeaseDocumentsListSuccessResponseResultLeaseDocuments

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsListSuccessResponseResultLeaseDocuments from a JSON string
get_lease_documents_list_success_response_result_lease_documents_instance = GetLeaseDocumentsListSuccessResponseResultLeaseDocuments.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsListSuccessResponseResultLeaseDocuments.to_json())

# convert the object into a dict
get_lease_documents_list_success_response_result_lease_documents_dict = get_lease_documents_list_success_response_result_lease_documents_instance.to_dict()
# create an instance of GetLeaseDocumentsListSuccessResponseResultLeaseDocuments from a dict
get_lease_documents_list_success_response_result_lease_documents_from_dict = GetLeaseDocumentsListSuccessResponseResultLeaseDocuments.from_dict(get_lease_documents_list_success_response_result_lease_documents_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


