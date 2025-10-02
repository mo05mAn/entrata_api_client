# SendLeasesSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**SendLeasesSuccessResponseResult**](SendLeasesSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_leases_success_response import SendLeasesSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeasesSuccessResponse from a JSON string
send_leases_success_response_instance = SendLeasesSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendLeasesSuccessResponse.to_json())

# convert the object into a dict
send_leases_success_response_dict = send_leases_success_response_instance.to_dict()
# create an instance of SendLeasesSuccessResponse from a dict
send_leases_success_response_from_dict = SendLeasesSuccessResponse.from_dict(send_leases_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


