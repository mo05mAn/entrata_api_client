# GetLeaseDocumentsListMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**lease_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**external_lease_id** | **int** | This is an optional field. This field accepts single value. This is the remote primary key that is associated to lease. | [optional] 
**document_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**file_types_code** | **str** | This is an optional field. This field accepts comma seperated multiple values. System code for file files | [optional] 
**show_deleted_file** | **int** | This is an optional field. This field accepts single value. If this flag is Yes then we are returning deleted documents else not. | [optional] 
**lease_status_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_documents_list_method_params import GetLeaseDocumentsListMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsListMethodParams from a JSON string
get_lease_documents_list_method_params_instance = GetLeaseDocumentsListMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsListMethodParams.to_json())

# convert the object into a dict
get_lease_documents_list_method_params_dict = get_lease_documents_list_method_params_instance.to_dict()
# create an instance of GetLeaseDocumentsListMethodParams from a dict
get_lease_documents_list_method_params_from_dict = GetLeaseDocumentsListMethodParams.from_dict(get_lease_documents_list_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


