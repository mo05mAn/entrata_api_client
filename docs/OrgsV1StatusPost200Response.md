# OrgsV1StatusPost200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**response** | [**GetStatusSuccessResponseResponse**](GetStatusSuccessResponseResponse.md) |  | 

## Example

```python
from entrata_api_client.models.orgs_v1_status_post200_response import OrgsV1StatusPost200Response

# TODO update the JSON string below
json = "{}"
# create an instance of OrgsV1StatusPost200Response from a JSON string
orgs_v1_status_post200_response_instance = OrgsV1StatusPost200Response.from_json(json)
# print the JSON string representation of the object
print(OrgsV1StatusPost200Response.to_json())

# convert the object into a dict
orgs_v1_status_post200_response_dict = orgs_v1_status_post200_response_instance.to_dict()
# create an instance of OrgsV1StatusPost200Response from a dict
orgs_v1_status_post200_response_from_dict = OrgsV1StatusPost200Response.from_dict(orgs_v1_status_post200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


