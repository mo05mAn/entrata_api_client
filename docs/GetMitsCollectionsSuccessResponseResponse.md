# GetMitsCollectionsSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **int** | Successful response code. | 
**result** | [**GetMitsCollectionsSuccessResponseResponseResult**](GetMitsCollectionsSuccessResponseResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_mits_collections_success_response_response import GetMitsCollectionsSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsCollectionsSuccessResponseResponse from a JSON string
get_mits_collections_success_response_response_instance = GetMitsCollectionsSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetMitsCollectionsSuccessResponseResponse.to_json())

# convert the object into a dict
get_mits_collections_success_response_response_dict = get_mits_collections_success_response_response_instance.to_dict()
# create an instance of GetMitsCollectionsSuccessResponseResponse from a dict
get_mits_collections_success_response_response_from_dict = GetMitsCollectionsSuccessResponseResponse.from_dict(get_mits_collections_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


