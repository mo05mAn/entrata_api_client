# GetWebsitesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**result** | [**GetWebsitesSuccessResponseResult**](GetWebsitesSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_websites_success_response import GetWebsitesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetWebsitesSuccessResponse from a JSON string
get_websites_success_response_instance = GetWebsitesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetWebsitesSuccessResponse.to_json())

# convert the object into a dict
get_websites_success_response_dict = get_websites_success_response_instance.to_dict()
# create an instance of GetWebsitesSuccessResponse from a dict
get_websites_success_response_from_dict = GetWebsitesSuccessResponse.from_dict(get_websites_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


