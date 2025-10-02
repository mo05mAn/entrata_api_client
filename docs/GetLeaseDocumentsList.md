# GetLeaseDocumentsList


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeaseDocumentsListMethod**](GetLeaseDocumentsListMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_documents_list import GetLeaseDocumentsList

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDocumentsList from a JSON string
get_lease_documents_list_instance = GetLeaseDocumentsList.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDocumentsList.to_json())

# convert the object into a dict
get_lease_documents_list_dict = get_lease_documents_list_instance.to_dict()
# create an instance of GetLeaseDocumentsList from a dict
get_lease_documents_list_from_dict = GetLeaseDocumentsList.from_dict(get_lease_documents_list_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


