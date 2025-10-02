# GetLeaseDocumentsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetLeaseDocumentsMethodParams**](GetLeaseDocumentsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_lease_documents_method import GetLeaseDocumentsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsMethod from a JSON string
get_lease_documents_method_instance = GetLeaseDocumentsMethod.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsMethod.to_json())

# convert the object into a dict
get_lease_documents_method_dict = get_lease_documents_method_instance.to_dict()
# create an instance of GetLeaseDocumentsMethod from a dict
get_lease_documents_method_from_dict = GetLeaseDocumentsMethod.from_dict(get_lease_documents_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


