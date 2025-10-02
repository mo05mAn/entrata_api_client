# GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the lease document. | 
**type** | **str** | Type of the lease document. | 
**name** | **str** | Name of the lease document file. | 
**title** | **str** | Title of the lease document. | 
**lease_id** | **str** | Unique identifier for the lease. | 
**external_lease_id** | **str** | External lease identifier used for cross-referencing. | 

## Example

```python
from openapi_client.models.get_lease_documents_list_success_response_result_lease_documents_lease_document_inner import GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner from a JSON string
get_lease_documents_list_success_response_result_lease_documents_lease_document_inner_instance = GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner.to_json())

# convert the object into a dict
get_lease_documents_list_success_response_result_lease_documents_lease_document_inner_dict = get_lease_documents_list_success_response_result_lease_documents_lease_document_inner_instance.to_dict()
# create an instance of GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner from a dict
get_lease_documents_list_success_response_result_lease_documents_lease_document_inner_from_dict = GetLeaseDocumentsListSuccessResponseResultLeaseDocumentsLeaseDocumentInner.from_dict(get_lease_documents_list_success_response_result_lease_documents_lease_document_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


