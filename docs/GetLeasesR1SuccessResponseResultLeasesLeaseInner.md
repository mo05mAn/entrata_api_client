# GetLeasesR1SuccessResponseResultLeasesLeaseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the lease | 
**lease_status_type_id** | **str** | ID representing the lease status type | 
**lease_sub_status** | **str** | Sub-status of the lease | 
**lease_type** | **str** | Type of the lease | 
**transfer_lease_id** | **str** | ID representing the transfer lease | 
**transfer_lease_property_id** | **str** | ID representing the transfer lease property | 
**lease_interval_status** | **str** | Status of the lease interval | 
**occupancy_type_id** | **str** | ID for the occupancy type | 
**occupancy_type** | **str** | Type of occupancy | 
**is_month_to_month** | **str** | Indicates if the lease is month to month | 
**lease_interval_id** | **str** | Unique identifier for the lease interval | 
**building_id** | **str** | Unique identifier for the building | 
**building_name** | **str** | Name of the building | 
**floor_plan_id** | **str** | Unique identifier for the floor plan | 
**floor_plan_name** | **str** | Name of the floor plan | 
**unit_id** | **str** | Unique identifier for the unit | 
**unit_number_space** | **str** | Unit number or space | 
**unit_space_id** | **str** | ID representing the unit space | 
**space_configuration** | **str** | Configuration of the space | 
**termination_start_date** | **str** | Start date for termination | 
**lease_intervals** | [**GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervals**](GetLeasesR1SuccessResponseResultLeasesLeaseInnerLeaseIntervals.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_leases_r1_success_response_result_leases_lease_inner import GetLeasesR1SuccessResponseResultLeasesLeaseInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR1SuccessResponseResultLeasesLeaseInner from a JSON string
get_leases_r1_success_response_result_leases_lease_inner_instance = GetLeasesR1SuccessResponseResultLeasesLeaseInner.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR1SuccessResponseResultLeasesLeaseInner.to_json())

# convert the object into a dict
get_leases_r1_success_response_result_leases_lease_inner_dict = get_leases_r1_success_response_result_leases_lease_inner_instance.to_dict()
# create an instance of GetLeasesR1SuccessResponseResultLeasesLeaseInner from a dict
get_leases_r1_success_response_result_leases_lease_inner_from_dict = GetLeasesR1SuccessResponseResultLeasesLeaseInner.from_dict(get_leases_r1_success_response_result_leases_lease_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


