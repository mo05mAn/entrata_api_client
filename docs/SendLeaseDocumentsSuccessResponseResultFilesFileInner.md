# SendLeaseDocumentsSuccessResponseResultFilesFileInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | Node identifier for the file | 
**file_id** | **str** | Unique identifier for the file | 
**file_name** | **str** | Name of the uploaded file | 
**status** | **str** | Status of the file upload | 
**message** | **str** | Message detailing the result of the upload | 

## Example

```python
from openapi_client.models.send_lease_documents_success_response_result_files_file_inner import SendLeaseDocumentsSuccessResponseResultFilesFileInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseDocumentsSuccessResponseResultFilesFileInner from a JSON string
send_lease_documents_success_response_result_files_file_inner_instance = SendLeaseDocumentsSuccessResponseResultFilesFileInner.from_json(json)
# print the JSON string representation of the object
print(SendLeaseDocumentsSuccessResponseResultFilesFileInner.to_json())

# convert the object into a dict
send_lease_documents_success_response_result_files_file_inner_dict = send_lease_documents_success_response_result_files_file_inner_instance.to_dict()
# create an instance of SendLeaseDocumentsSuccessResponseResultFilesFileInner from a dict
send_lease_documents_success_response_result_files_file_inner_from_dict = SendLeaseDocumentsSuccessResponseResultFilesFileInner.from_dict(send_lease_documents_success_response_result_files_file_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


