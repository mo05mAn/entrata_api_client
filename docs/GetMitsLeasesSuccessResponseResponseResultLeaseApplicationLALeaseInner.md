# GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**List[GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerIdentificationInner]**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerIdentificationInner.md) |  | 
**accounting_data** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingData**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingData.md) |  | 
**lease_events** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerLeaseEvents**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerLeaseEvents.md) |  | 
**var_property** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty.md) |  | 
**status** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerStatus**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerStatus.md) |  | 
**unit** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerUnit.md) |  | 

## Example

```python
from openapi_client.models.get_mits_leases_success_response_response_result_lease_application_la_lease_inner import GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner from a JSON string
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_instance = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_dict = get_mits_leases_success_response_response_result_lease_application_la_lease_inner_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner from a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_from_dict = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner.from_dict(get_mits_leases_success_response_response_result_lease_application_la_lease_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


