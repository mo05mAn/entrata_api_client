# GetLeadPickListsR1SuccessResponseResponse

The response data containing request information and result.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | [optional] 
**code** | **int** | Successful response code. | [optional] 
**result** | [**GetLeadPickListsR1SuccessResponseResponseResult**](GetLeadPickListsR1SuccessResponseResponseResult.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_lead_pick_lists_r1_success_response_response import GetLeadPickListsR1SuccessResponseResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR1SuccessResponseResponse from a JSON string
get_lead_pick_lists_r1_success_response_response_instance = GetLeadPickListsR1SuccessResponseResponse.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR1SuccessResponseResponse.to_json())

# convert the object into a dict
get_lead_pick_lists_r1_success_response_response_dict = get_lead_pick_lists_r1_success_response_response_instance.to_dict()
# create an instance of GetLeadPickListsR1SuccessResponseResponse from a dict
get_lead_pick_lists_r1_success_response_response_from_dict = GetLeadPickListsR1SuccessResponseResponse.from_dict(get_lead_pick_lists_r1_success_response_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


