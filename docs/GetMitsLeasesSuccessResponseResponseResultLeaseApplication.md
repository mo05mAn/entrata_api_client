# GetMitsLeasesSuccessResponseResponseResultLeaseApplication


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tenant** | [**List[GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner]**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationTenantInner.md) |  | 
**la_lease** | [**List[GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner]**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInner.md) |  | 

## Example

```python
from openapi_client.models.get_mits_leases_success_response_response_result_lease_application import GetMitsLeasesSuccessResponseResponseResultLeaseApplication

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplication from a JSON string
get_mits_leases_success_response_response_result_lease_application_instance = GetMitsLeasesSuccessResponseResponseResultLeaseApplication.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponseResultLeaseApplication.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_result_lease_application_dict = get_mits_leases_success_response_response_result_lease_application_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplication from a dict
get_mits_leases_success_response_response_result_lease_application_from_dict = GetMitsLeasesSuccessResponseResponseResultLeaseApplication.from_dict(get_mits_leases_success_response_response_result_lease_application_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


