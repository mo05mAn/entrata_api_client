# GetMitsLeadsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response code indicating the result. | 
**result** | [**GetMitsLeadsSuccessResponseResult**](GetMitsLeadsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_mits_leads_success_response import GetMitsLeadsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsSuccessResponse from a JSON string
get_mits_leads_success_response_instance = GetMitsLeadsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsSuccessResponse.to_json())

# convert the object into a dict
get_mits_leads_success_response_dict = get_mits_leads_success_response_instance.to_dict()
# create an instance of GetMitsLeadsSuccessResponse from a dict
get_mits_leads_success_response_from_dict = GetMitsLeadsSuccessResponse.from_dict(get_mits_leads_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


