# GetLeadsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **str** | The status code of the response. | 
**result** | [**GetLeadsSuccessResponseResult**](GetLeadsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_leads_success_response import GetLeadsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponse from a JSON string
get_leads_success_response_instance = GetLeadsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponse.to_json())

# convert the object into a dict
get_leads_success_response_dict = get_leads_success_response_instance.to_dict()
# create an instance of GetLeadsSuccessResponse from a dict
get_leads_success_response_from_dict = GetLeadsSuccessResponse.from_dict(get_leads_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


