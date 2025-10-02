# GetExpiringLeasesSuccessResponseResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**result** | [**GetExpiringLeasesSuccessResponseResponseResult**](GetExpiringLeasesSuccessResponseResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_expiring_leases_success_response_response import GetExpiringLeasesSuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetExpiringLeasesSuccessResponseResponse from a JSON string
get_expiring_leases_success_response_response_instance = GetExpiringLeasesSuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetExpiringLeasesSuccessResponseResponse.to_json())

# convert the object into a dict
get_expiring_leases_success_response_response_dict = get_expiring_leases_success_response_response_instance.to_dict()
# create an instance of GetExpiringLeasesSuccessResponseResponse from a dict
get_expiring_leases_success_response_response_from_dict = GetExpiringLeasesSuccessResponseResponse.from_dict(get_expiring_leases_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


