# GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAttributes**](GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAttributes.md) |  | 
**name** | **str** | Name of the resident. | 
**phone_number** | **str** | Phone number of the resident. | 
**email_address** | **str** | Email address of the resident. | [optional] 
**address** | [**GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress**](GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResidentAddress.md) |  | 

## Example

```python
from entrata_api_client.models.get_expiring_leases_success_response_response_result_leases_lease_inner_resident import GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident

# TODO update the JSON string below
json = "{}"
# create an instance of GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident from a JSON string
get_expiring_leases_success_response_response_result_leases_lease_inner_resident_instance = GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident.from_json(json)
# print the JSON string representation of the object
print(GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident.to_json())

# convert the object into a dict
get_expiring_leases_success_response_response_result_leases_lease_inner_resident_dict = get_expiring_leases_success_response_response_result_leases_lease_inner_resident_instance.to_dict()
# create an instance of GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident from a dict
get_expiring_leases_success_response_response_result_leases_lease_inner_resident_from_dict = GetExpiringLeasesSuccessResponseResponseResultLeasesLeaseInnerResident.from_dict(get_expiring_leases_success_response_response_result_leases_lease_inner_resident_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


