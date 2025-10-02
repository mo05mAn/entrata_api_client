# GetLeaseDocumentsSuccessResponseResultLeaseDocuments


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_document** | [**Dict[str, GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue]**](GetLeaseDocumentsSuccessResponseResultLeaseDocumentsLeaseDocumentValue.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_documents_success_response_result_lease_documents import GetLeaseDocumentsSuccessResponseResultLeaseDocuments

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsSuccessResponseResultLeaseDocuments from a JSON string
get_lease_documents_success_response_result_lease_documents_instance = GetLeaseDocumentsSuccessResponseResultLeaseDocuments.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsSuccessResponseResultLeaseDocuments.to_json())

# convert the object into a dict
get_lease_documents_success_response_result_lease_documents_dict = get_lease_documents_success_response_result_lease_documents_instance.to_dict()
# create an instance of GetLeaseDocumentsSuccessResponseResultLeaseDocuments from a dict
get_lease_documents_success_response_result_lease_documents_from_dict = GetLeaseDocumentsSuccessResponseResultLeaseDocuments.from_dict(get_lease_documents_success_response_result_lease_documents_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


