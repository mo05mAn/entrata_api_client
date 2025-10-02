# GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnitIdentification**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnitIdentification.md) |  | 
**marketing_name** | **str** | Marketing name of the unit | 
**unit_type** | **str** | Type of the unit | 
**unit_leased_status** | **str** | Leased status of the unit | 
**address** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnitAddress**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnitAddress.md) |  | 

## Example

```python
from entrata_api_client.models.get_mits_leases_success_response_response_result_lease_application_la_lease_inner_unit import GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit from a JSON string
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_unit_instance = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_unit_dict = get_mits_leases_success_response_response_result_lease_application_la_lease_inner_unit_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit from a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_unit_from_dict = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit.from_dict(get_mits_leases_success_response_response_result_lease_application_la_lease_inner_unit_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


