# GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the lease document. | 
**applies_to** | **str** | Indicates who the document applies to. | 
**type** | **str** | Type of the lease document. | 
**title** | **str** | Title of the lease document. | 
**name** | **str** | Filename of the lease document. | 
**path** | **str** | Path where the document is stored. | 
**file_data** | **str** | Data related to the file (empty in this case). | 
**added_on** | **str** | Timestamp when the document was added. | 

## Example

```python
from openapi_client.models.get_lease_documents_success_response_result_lease_documents_lease_document_value import GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue from a JSON string
get_lease_documents_success_response_result_lease_documents_lease_document_value_instance = GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue.to_json())

# convert the object into a dict
get_lease_documents_success_response_result_lease_documents_lease_document_value_dict = get_lease_documents_success_response_result_lease_documents_lease_document_value_instance.to_dict()
# create an instance of GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue from a dict
get_lease_documents_success_response_result_lease_documents_lease_document_value_from_dict = GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue.from_dict(get_lease_documents_success_response_result_lease_documents_lease_document_value_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


