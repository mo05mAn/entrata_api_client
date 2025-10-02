# SendLeaseDocumentsRequestBodyMethodParamsFilesFileInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_name** | **str** | This is a required field. This will be the name of the file being uploaded. | 
**lease_file_type** | **str** | This is a optional field. This field accepts single value. This is conditionally required if fileTypeId is not provided. This will be the type of the file being uploaded. | [optional] 
**file_type_id** | **int** | This is a optional field. This field accepts single value. This is conditionally required if leaseFileType is not provided. | [optional] 
**is_show_in_resident_portal** | **int** | This is a optional field. This will specify the visibility of uploaded document in the resident portal. | [optional] 
**customer_ids** | **str** | This is a optional field. This will accepts comma separated multiple values. If provided this file will attach to the mentioned customers. if skipped, the file will be attached to all the customers of the lease. | [optional] 

## Example

```python
from entrata_api_client.models.send_lease_documents_request_body_method_params_files_file_inner import SendLeaseDocumentsRequestBodyMethodParamsFilesFileInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeaseDocumentsRequestBodyMethodParamsFilesFileInner from a JSON string
send_lease_documents_request_body_method_params_files_file_inner_instance = SendLeaseDocumentsRequestBodyMethodParamsFilesFileInner.from_json(json)
# print the JSON string representation of the object
print(SendLeaseDocumentsRequestBodyMethodParamsFilesFileInner.to_json())

# convert the object into a dict
send_lease_documents_request_body_method_params_files_file_inner_dict = send_lease_documents_request_body_method_params_files_file_inner_instance.to_dict()
# create an instance of SendLeaseDocumentsRequestBodyMethodParamsFilesFileInner from a dict
send_lease_documents_request_body_method_params_files_file_inner_from_dict = SendLeaseDocumentsRequestBodyMethodParamsFilesFileInner.from_dict(send_lease_documents_request_body_method_params_files_file_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


