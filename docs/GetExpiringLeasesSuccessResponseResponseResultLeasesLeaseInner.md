# GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerAttributes**](GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerAttributes.md) |  | 
**resident** | [**GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident**](GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident.md) |  | 
**unit** | **str** | Unit number associated with the lease. | [optional] 
**lease_status** | **str** | Current status of the lease (e.g., Current, Notice). | 
**lease_starts** | **str** | Start date of the lease. | 
**lease_expires** | **str** | Expiration date of the lease. | 
**notice_date** | **str** | Date the notice was given (if applicable). | [optional] 

## Example

```python
from openapi_client.models.get_expiring_leases_success_response_response_result_leases_lease_inner import GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInner from a JSON string
get_expiring_leases_success_response_response_result_leases_lease_inner_instance = GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInner.from_json(json)
# print the JSON string representation of the object
print(GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInner.to_json())

# convert the object into a dict
get_expiring_leases_success_response_response_result_leases_lease_inner_dict = get_expiring_leases_success_response_response_result_leases_lease_inner_instance.to_dict()
# create an instance of GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInner from a dict
get_expiring_leases_success_response_response_result_leases_lease_inner_from_dict = GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInner.from_dict(get_expiring_leases_success_response_response_result_leases_lease_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


