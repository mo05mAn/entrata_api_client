# UpdateLeaseSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request | 
**code** | **int** | Response status code | 
**result** | [**UpdateLeaseSuccessResponseResult**](UpdateLeaseSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.update_lease_success_response import UpdateLeaseSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeaseSuccessResponse from a JSON string
update_lease_success_response_instance = UpdateLeaseSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateLeaseSuccessResponse.to_json())

# convert the object into a dict
update_lease_success_response_dict = update_lease_success_response_instance.to_dict()
# create an instance of UpdateLeaseSuccessResponse from a dict
update_lease_success_response_from_dict = UpdateLeaseSuccessResponse.from_dict(update_lease_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


