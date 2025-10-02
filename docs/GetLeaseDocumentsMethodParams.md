# GetLeaseDocumentsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**lease_id** | **int** | This is an optional field. This field accepts single value. Lease Id - Required if externalLeaseId is not provided | [optional] 
**external_lease_id** | **int** | This is an optional field. This field accepts single value. The remote primary key which is associated to lease. Required if leas eId is not provided. | [optional] 
**document_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**file_types_code** | **str** | This is an optional field. This field accepts comma seperated multiple values. System code for file files | [optional] 
**added_on_from_date** | **date** | This is an optional field. This field accepts single value. If provided, this will return the documents which have AddedOn dates o n or after the date provided. | [optional] 
**show_deleted_file** | **int** | This is an optional field. This field accepts single value. If this flag is Yes then we are returning deleted documents else not. | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_documents_method_params import GetLeaseDocumentsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsMethodParams from a JSON string
get_lease_documents_method_params_instance = GetLeaseDocumentsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsMethodParams.to_json())

# convert the object into a dict
get_lease_documents_method_params_dict = get_lease_documents_method_params_instance.to_dict()
# create an instance of GetLeaseDocumentsMethodParams from a dict
get_lease_documents_method_params_from_dict = GetLeaseDocumentsMethodParams.from_dict(get_lease_documents_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


