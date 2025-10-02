# GetVendorsSuccessResponseResultVendorsVendorInnerAccountsAccountInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_id** | **str** | Unique identifier for the account. | 
**account_number** | **str** | Account number. | 
**description** | **str** | Description of the account. | 
**remittance_id** | **str** | ID of the remittance. | 
**remittance_name** | **str** | Name of the remittance. | 
**remittance_payment_type_id** | **str** | ID of the remittance payment type. | 
**gl_account_id** | **str** | General ledger account ID. | 
**location_name** | **str** | Location name. | 
**utility_bill_receipt_type_id** | **str** | Utility bill receipt type ID. | 
**is_audit_invoice** | **str** | Indicates if the invoice is for audit purposes. | [optional] 
**is_disabled** | **str** | Indicates if the account is disabled. | [optional] 
**is_capture_invoice_total_only** | **str** | Indicates if only the invoice total should be captured. | [optional] 

## Example

```python
from openapi_client.models.get_vendors_success_response_result_vendors_vendor_inner_accounts_account_inner import GetVendorsSuccessResponseResultVendorsVendorInnerAccountsAccountInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerAccountsAccountInner from a JSON string
get_vendors_success_response_result_vendors_vendor_inner_accounts_account_inner_instance = GetVendorsSuccessResponseResultVendorsVendorInnerAccountsAccountInner.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendorsVendorInnerAccountsAccountInner.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_vendor_inner_accounts_account_inner_dict = get_vendors_success_response_result_vendors_vendor_inner_accounts_account_inner_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendorsVendorInnerAccountsAccountInner from a dict
get_vendors_success_response_result_vendors_vendor_inner_accounts_account_inner_from_dict = GetVendorsSuccessResponseResultVendorsVendorInnerAccountsAccountInner.from_dict(get_vendors_success_response_result_vendors_vendor_inner_accounts_account_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


