# GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the lease | 
**lease_status_type_id** | **str** | Status type identifier for the lease | 
**property_id** | **str** | Property identifier | 
**move_in_date** | **str** | Move-in date of the lease | 
**move_out_date** | **str** | Move-out date of the lease | 
**transfer_date** | **str** | Transfer date of the lease | 
**property_name** | **str** | Name of the property | 
**lease_interval_status** | **str** | Status of the lease interval | 
**occupancy_type_id** | **str** | Occupancy type ID | 
**occupancy_type** | **str** | Type of occupancy | 
**is_month_to_month** | **int** | Indicates if the lease is month-to-month | 
**lease_interval_id** | **str** | Lease interval ID | 
**floor_plan_id** | **str** | ID of the floor plan | 
**floor_plan_name** | **str** | Name of the floor plan | 
**payment_allowance_type** | **str** | Type of payment allowance | 
**space_configuration** | **str** | Configuration of the unit space | 
**customers** | [**GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomers**](GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerCustomers.md) |  | 
**unit_id** | **str** | Unit ID of the lease | 
**unit_spaces** | [**GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerUnitSpaces**](GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerUnitSpaces.md) |  | 
**lease_intervals** | [**GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervals**](GetLeasesR2SuccessResponseResponseResultLeasesLeaseInnerLeaseIntervals.md) |  | 

## Example

```python
from openapi_client.models.get_leases_r2_success_response_response_result_leases_lease_inner import GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner from a JSON string
get_leases_r2_success_response_response_result_leases_lease_inner_instance = GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner.from_json(json)
# print the JSON string representation of the object
print(GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner.to_json())

# convert the object into a dict
get_leases_r2_success_response_response_result_leases_lease_inner_dict = get_leases_r2_success_response_response_result_leases_lease_inner_instance.to_dict()
# create an instance of GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner from a dict
get_leases_r2_success_response_response_result_leases_lease_inner_from_dict = GetLeasesR2SuccessResponseResponseResultLeasesLeaseInner.from_dict(get_leases_r2_success_response_response_result_leases_lease_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


