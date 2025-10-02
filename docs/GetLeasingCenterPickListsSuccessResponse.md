# GetLeasingCenterPickListsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Identifier of the request | 
**code** | **str** | Status code of the response | 
**result** | [**GetLeasingCenterPickListsSuccessResponseResult**](GetLeasingCenterPickListsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_leasing_center_pick_lists_success_response import GetLeasingCenterPickListsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasingCenterPickListsSuccessResponse from a JSON string
get_leasing_center_pick_lists_success_response_instance = GetLeasingCenterPickListsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeasingCenterPickListsSuccessResponse.to_json())

# convert the object into a dict
get_leasing_center_pick_lists_success_response_dict = get_leasing_center_pick_lists_success_response_instance.to_dict()
# create an instance of GetLeasingCenterPickListsSuccessResponse from a dict
get_leasing_center_pick_lists_success_response_from_dict = GetLeasingCenterPickListsSuccessResponse.from_dict(get_leasing_center_pick_lists_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


