# GetVendorsSuccessResponseResultVendorsVendorInnerApRemittancesApRemittanceInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the AP remittance. | 
**name** | **str** | Name of the AP remittance. | 
**ap_payment_type_id** | **str** | Payment type identifier. | 
**ap_payment_type** | **str** | Type of payment. | 
**check_account_type_id** | **str** | Account type identifier. | 
**check_account_type** | **str** | Type of check account. | 
**is_default** | **str** | Indicates if this remittance is the default. | 

## Example

```python
from openapi_client.models.get_vendors_success_response_result_vendors_vendor_inner_ap_remittances_ap_remittance_inner import GetVendorsSuccessResponseResultVendorsVendorInnerApRemittancesApRemittanceInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerApRemittancesApRemittanceInner from a JSON string
get_vendors_success_response_result_vendors_vendor_inner_ap_remittances_ap_remittance_inner_instance = GetVendorsSuccessResponseResultVendorsVendorInnerApRemittancesApRemittanceInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendorsVendorInnerApRemittancesApRemittanceInner.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_vendor_inner_ap_remittances_ap_remittance_inner_dict = get_vendors_success_response_result_vendors_vendor_inner_ap_remittances_ap_remittance_inner_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerApRemittancesApRemittanceInner from a dict
get_vendors_success_response_result_vendors_vendor_inner_ap_remittances_ap_remittance_inner_from_dict = GetVendorsSuccessResponseResultVendorsVendorInnerApRemittancesApRemittanceInner.from_dict(get_vendors_success_response_result_vendors_vendor_inner_ap_remittances_ap_remittance_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


