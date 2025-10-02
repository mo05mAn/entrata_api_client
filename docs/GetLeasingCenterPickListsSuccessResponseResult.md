# GetLeasingCenterPickListsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**call_sources** | [**GetLeasingCenterPickListsSuccessResponseResultCallSources**](GetLeasingCenterPickListsSuccessResponseResultCallSources.md) |  | 
**call_types** | [**GetLeasingCenterPickListsSuccessResponseResultCallTypes**](GetLeasingCenterPickListsSuccessResponseResultCallTypes.md) |  | 
**call_results** | [**GetLeasingCenterPickListsSuccessResponseResultCallResults**](GetLeasingCenterPickListsSuccessResponseResultCallResults.md) |  | 

## Example

```python
from entrata_api_client.models.get_leasing_center_pick_lists_success_response_result import GetLeasingCenterPickListsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasingCenterPickListsSuccessResponseResult from a JSON string
get_leasing_center_pick_lists_success_response_result_instance = GetLeasingCenterPickListsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeasingCenterPickListsSuccessResponseResult.to_json())

# convert the object into a dict
get_leasing_center_pick_lists_success_response_result_dict = get_leasing_center_pick_lists_success_response_result_instance.to_dict()
# create an instance of GetLeasingCenterPickListsSuccessResponseResult from a dict
get_leasing_center_pick_lists_success_response_result_from_dict = GetLeasingCenterPickListsSuccessResponseResult.from_dict(get_leasing_center_pick_lists_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


