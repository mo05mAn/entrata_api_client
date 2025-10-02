# GetLeaseDetailsR2SuccessResponseResultLeasesLease


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_id** | **str** | Unique identifier for the lease. | 
**name** | **str** | Name of the resident. | 
**property_unit_id** | **str** | Unique identifier for the property unit. | 
**unit_number** | **str** | Unit number of the leased property. | 
**add_ons** | [**GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOns**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseAddOns.md) |  | 
**scheduled_charges** | [**GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges**](GetLeaseDetailsR2SuccessResponseResultLeasesLeaseScheduledCharges.md) |  | 

## Example

```python
from entrata_api_client.models.get_lease_details_r2_success_response_result_leases_lease import GetLeaseDetailsR2SuccessResponseResultLeasesLease

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLease from a JSON string
get_lease_details_r2_success_response_result_leases_lease_instance = GetLeaseDetailsR2SuccessResponseResultLeasesLease.from_json(json)
# print the JSON string representation of the object
print(GetLeaseDetailsR2SuccessResponseResultLeasesLease.to_json())

# convert the object into a dict
get_lease_details_r2_success_response_result_leases_lease_dict = get_lease_details_r2_success_response_result_leases_lease_instance.to_dict()
# create an instance of GetLeaseDetailsR2SuccessResponseResultLeasesLease from a dict
get_lease_details_r2_success_response_result_leases_lease_from_dict = GetLeaseDetailsR2SuccessResponseResultLeasesLease.from_dict(get_lease_details_r2_success_response_result_leases_lease_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


