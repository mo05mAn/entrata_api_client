# GetLeasePickListSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | Status code of the response. | 
**result** | [**GetLeasePickListSuccessResponseResult**](GetLeasePickListSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_pick_list_success_response import GetLeasePickListSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasePickListSuccessResponse from a JSON string
get_lease_pick_list_success_response_instance = GetLeasePickListSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeasePickListSuccessResponse.to_json())

# convert the object into a dict
get_lease_pick_list_success_response_dict = get_lease_pick_list_success_response_instance.to_dict()
# create an instance of GetLeasePickListSuccessResponse from a dict
get_lease_pick_list_success_response_from_dict = GetLeasePickListSuccessResponse.from_dict(get_lease_pick_list_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


