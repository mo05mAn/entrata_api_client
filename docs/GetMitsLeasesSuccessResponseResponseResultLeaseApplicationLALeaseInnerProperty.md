# GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerPropertyIdentification**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerPropertyIdentification.md) |  | 
**marketing_name** | **str** | Marketing name of the property | 
**address** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerPropertyAddress**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerPropertyAddress.md) |  | 

## Example

```python
from openapi_client.models.get_mits_leases_success_response_response_result_lease_application_la_lease_inner_property import GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty from a JSON string
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_property_instance = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_property_dict = get_mits_leases_success_response_response_result_lease_application_la_lease_inner_property_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty from a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_property_from_dict = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerProperty.from_dict(get_mits_leases_success_response_response_result_lease_application_la_lease_inner_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


