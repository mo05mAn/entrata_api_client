# OrgsV1LeadsPost200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response status code. | 
**result** | [**UpdateLeadsR2SuccessResponseResult**](UpdateLeadsR2SuccessResponseResult.md) |  | 
**response** | [**GetLeadPickListsR1SuccessResponseResponse**](GetLeadPickListsR1SuccessResponseResponse.md) |  | 

## Example

```python
from openapi_client.models.orgs_v1_leads_post200_response import OrgsV1LeadsPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of OrgsV1LeadsPost200Response from a JSON string
orgs_v1_leads_post200_response_instance = OrgsV1LeadsPost200Response.from_json(json)
# print the JSON string representation of the object
print(OrgsV1LeadsPost200Response.to_json())

# convert the object into a dict
orgs_v1_leads_post200_response_dict = orgs_v1_leads_post200_response_instance.to_dict()
# create an instance of OrgsV1LeadsPost200Response from a dict
orgs_v1_leads_post200_response_from_dict = OrgsV1LeadsPost200Response.from_dict(orgs_v1_leads_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


