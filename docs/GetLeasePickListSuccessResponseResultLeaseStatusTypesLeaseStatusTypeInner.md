# GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique identifier for the lease status type. | 
**name** | **str** | Name of the lease status type. | 
**type** | **str** | Type of the lease status. | 

## Example

```python
from entrata_api_client.models.get_lease_pick_list_success_response_result_lease_status_types_lease_status_type_inner import GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner from a JSON string
get_lease_pick_list_success_response_result_lease_status_types_lease_status_type_inner_instance = GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner.from_json(json)
# print the JSON string representation of the object
print(GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner.to_json())

# convert the object into a dict
get_lease_pick_list_success_response_result_lease_status_types_lease_status_type_inner_dict = get_lease_pick_list_success_response_result_lease_status_types_lease_status_type_inner_instance.to_dict()
# create an instance of GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner from a dict
get_lease_pick_list_success_response_result_lease_status_types_lease_status_type_inner_from_dict = GetLeasePickListSuccessResponseResultLeaseStatusTypesLeaseStatusTypeInner.from_dict(get_lease_pick_list_success_response_result_lease_status_types_lease_status_type_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


