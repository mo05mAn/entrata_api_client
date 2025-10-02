# GetLeadPickListsR2SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**code** | **str** | The response code indicating the result. | 
**result** | [**GetLeadPickListsR2SuccessResponseResult**](GetLeadPickListsR2SuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response import GetLeadPickListsR2SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponse from a JSON string
get_lead_pick_lists_r2_success_response_instance = GetLeadPickListsR2SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponse.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_dict = get_lead_pick_lists_r2_success_response_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponse from a dict
get_lead_pick_lists_r2_success_response_from_dict = GetLeadPickListsR2SuccessResponse.from_dict(get_lead_pick_lists_r2_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


