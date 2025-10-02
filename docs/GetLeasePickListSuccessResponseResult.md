# GetLeasePickListSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_status_types** | [**GetLeasePickListSuccessResponseResultLeaseStatusTypes**](GetLeasePickListSuccessResponseResultLeaseStatusTypes.md) |  | 
**lease_file_types** | [**GetLeasePickListSuccessResponseResultLeaseFileTypes**](GetLeasePickListSuccessResponseResultLeaseFileTypes.md) |  | 
**charge_timings** | [**GetLeasePickListSuccessResponseResultChargeTimings**](GetLeasePickListSuccessResponseResultChargeTimings.md) |  | 
**charge_code_types** | [**GetLeasePickListSuccessResponseResultChargeCodeTypes**](GetLeasePickListSuccessResponseResultChargeCodeTypes.md) |  | 
**event_tags** | [**GetLeasePickListSuccessResponseResultEventTags**](GetLeasePickListSuccessResponseResultEventTags.md) |  | 

## Example

```python
from openapi_client.models.get_lease_pick_list_success_response_result import GetLeasePickListSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasePickListSuccessResponseResult from a JSON string
get_lease_pick_list_success_response_result_instance = GetLeasePickListSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeasePickListSuccessResponseResult.to_json())

# convert the object into a dict
get_lease_pick_list_success_response_result_dict = get_lease_pick_list_success_response_result_instance.to_dict()
# create an instance of GetLeasePickListSuccessResponseResult from a dict
get_lease_pick_list_success_response_result_from_dict = GetLeasePickListSuccessResponseResult.from_dict(get_lease_pick_list_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


