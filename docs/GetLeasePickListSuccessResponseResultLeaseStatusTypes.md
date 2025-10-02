# GetLeasePickListSuccessResponseResultLeaseStatusTypes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_status_type** | [**List[GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner]**](GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_pick_list_success_response_result_lease_status_types import GetLeasePickListSuccessResponseResultLeaseStatusTypes

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasePickListSuccessResponseResultLeaseStatusTypes from a JSON string
get_lease_pick_list_success_response_result_lease_status_types_instance = GetLeasePickListSuccessResponseResultLeaseStatusTypes.from_json(json)
# print the JSON string representation of the object
print(GetLeasePickListSuccessResponseResultLeaseStatusTypes.to_json())

# convert the object into a dict
get_lease_pick_list_success_response_result_lease_status_types_dict = get_lease_pick_list_success_response_result_lease_status_types_instance.to_dict()
# create an instance of GetLeasePickListSuccessResponseResultLeaseStatusTypes from a dict
get_lease_pick_list_success_response_result_lease_status_types_from_dict = GetLeasePickListSuccessResponseResultLeaseStatusTypes.from_dict(get_lease_pick_list_success_response_result_lease_status_types_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


