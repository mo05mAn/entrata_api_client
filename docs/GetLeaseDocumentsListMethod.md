# GetLeaseDocumentsListMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetLeaseDocumentsListMethodParams**](GetLeaseDocumentsListMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_documents_list_method import GetLeaseDocumentsListMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsListMethod from a JSON string
get_lease_documents_list_method_instance = GetLeaseDocumentsListMethod.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsListMethod.to_json())

# convert the object into a dict
get_lease_documents_list_method_dict = get_lease_documents_list_method_instance.to_dict()
# create an instance of GetLeaseDocumentsListMethod from a dict
get_lease_documents_list_method_from_dict = GetLeaseDocumentsListMethod.from_dict(get_lease_documents_list_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


