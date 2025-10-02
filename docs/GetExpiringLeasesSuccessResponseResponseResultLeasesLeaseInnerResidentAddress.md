# GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**street_line1** | **str** | First line of the address. | 
**street_line2** | **str** | Second line of the address. | [optional] 
**city** | **str** | City of the address. | 
**state_code** | **str** | State code of the address. | 
**postal_code** | **str** | Postal code of the address. | 

## Example

```python
from entrata_api_client.models.get_expiring_leases_success_response_response_result_leases_lease_inner_resident_address import GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress

# TODO update the JSON string below
json = "{}"
# create an instance of GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress from a JSON string
get_expiring_leases_success_response_response_result_leases_lease_inner_resident_address_instance = GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress.from_json(json)
# print the JSON string representation of the object
print(GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress.to_json())

# convert the object into a dict
get_expiring_leases_success_response_response_result_leases_lease_inner_resident_address_dict = get_expiring_leases_success_response_response_result_leases_lease_inner_resident_address_instance.to_dict()
# create an instance of GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress from a dict
get_expiring_leases_success_response_response_result_leases_lease_inner_resident_address_from_dict = GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress.from_dict(get_expiring_leases_success_response_response_result_leases_lease_inner_resident_address_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


