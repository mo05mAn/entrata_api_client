# GetTransactionTagLists


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetTransactionTagListsMethod**](GetTransactionTagListsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_transaction_tag_lists import GetTransactionTagLists

# TODO update the JSON string below
json = "{}"
# create an instance of GetTransactionTagLists from a JSON string
get_transaction_tag_lists_instance = GetTransactionTagLists.from_json(json)
# print the JSON string representation of the object
print(GetTransactionTagLists.to_json())

# convert the object into a dict
get_transaction_tag_lists_dict = get_transaction_tag_lists_instance.to_dict()
# create an instance of GetTransactionTagLists from a dict
get_transaction_tag_lists_from_dict = GetTransactionTagLists.from_dict(get_transaction_tag_lists_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


