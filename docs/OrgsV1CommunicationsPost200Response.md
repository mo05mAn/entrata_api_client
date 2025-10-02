# OrgsV1CommunicationsPost200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetMarketingPreferencePickListSuccessResponseResponse**](GetMarketingPreferencePickListSuccessResponseResponse.md) |  | 
**request_id** | **str** | The unique identifier for the request | 
**code** | **int** | Response code indicating the status of the request | 
**result** | [**GetMarketingPreferencesSuccessResponseResult**](GetMarketingPreferencesSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.orgs_v1_communications_post200_response import OrgsV1CommunicationsPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of OrgsV1CommunicationsPost200Response from a JSON string
orgs_v1_communications_post200_response_instance = OrgsV1CommunicationsPost200Response.from_json(json)
# print the JSON string representation of the object
print(OrgsV1CommunicationsPost200Response.to_json())

# convert the object into a dict
orgs_v1_communications_post200_response_dict = orgs_v1_communications_post200_response_instance.to_dict()
# create an instance of OrgsV1CommunicationsPost200Response from a dict
orgs_v1_communications_post200_response_from_dict = OrgsV1CommunicationsPost200Response.from_dict(orgs_v1_communications_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


