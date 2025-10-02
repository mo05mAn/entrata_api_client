# GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**start** | **str** | Start date of the charge period | 
**end** | **str** | End date of the charge period | 
**frequency** | **str** | Frequency of the charge | 
**charge** | [**GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSetCharge**](GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSetCharge.md) |  | 

## Example

```python
from openapi_client.models.get_mits_leases_success_response_response_result_lease_application_la_lease_inner_accounting_data_charge_set import GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSet

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSet from a JSON string
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_accounting_data_charge_set_instance = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSet.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSet.to_json())

# convert the object into a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_accounting_data_charge_set_dict = get_mits_leases_success_response_response_result_lease_application_la_lease_inner_accounting_data_charge_set_instance.to_dict()
# create an instance of GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSet from a dict
get_mits_leases_success_response_response_result_lease_application_la_lease_inner_accounting_data_charge_set_from_dict = GetMitsLeasesSuccessResponseResponseResultLeaseApplicationLALeaseInnerAccountingDataChargeSet.from_dict(get_mits_leases_success_response_response_result_lease_application_la_lease_inner_accounting_data_charge_set_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


