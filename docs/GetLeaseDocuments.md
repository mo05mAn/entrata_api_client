# GetLeaseDocuments


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeaseDocumentsMethod**](GetLeaseDocumentsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_documents import GetLeaseDocuments

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocuments from a JSON string
get_lease_documents_instance = GetLeaseDocuments.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocuments.to_json())

# convert the object into a dict
get_lease_documents_dict = get_lease_documents_instance.to_dict()
# create an instance of GetLeaseDocuments from a dict
get_lease_documents_from_dict = GetLeaseDocuments.from_dict(get_lease_documents_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


