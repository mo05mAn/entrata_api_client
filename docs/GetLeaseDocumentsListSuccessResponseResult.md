# GetLeaseDocumentsListSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_documents** | [**GetLeaseDocumentsListSuccessResponseResultLeaseDocuments**](GetLeaseDocumentsListSuccessResponseResultLeaseDocuments.md) |  | 

## Example

```python
from openapi_client.models.get_lease_documents_list_success_response_result import GetLeaseDocumentsListSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsListSuccessResponseResult from a JSON string
get_lease_documents_list_success_response_result_instance = GetLeaseDocumentsListSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsListSuccessResponseResult.to_json())

# convert the object into a dict
get_lease_documents_list_success_response_result_dict = get_lease_documents_list_success_response_result_instance.to_dict()
# create an instance of GetLeaseDocumentsListSuccessResponseResult from a dict
get_lease_documents_list_success_response_result_from_dict = GetLeaseDocumentsListSuccessResponseResult.from_dict(get_lease_documents_list_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


