# GetVendorPickListsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_category_types** | [**GetVendorPickListsSuccessResponseResultVendorCategoryTypes**](GetVendorPickListsSuccessResponseResultVendorCategoryTypes.md) |  | [optional] 
**owner_types** | [**GetVendorPickListsSuccessResponseResultOwnerTypes**](GetVendorPickListsSuccessResponseResultOwnerTypes.md) |  | [optional] 
**ap_payee_terms** | [**GetVendorPickListsSuccessResponseResultApPayeeTerms**](GetVendorPickListsSuccessResponseResultApPayeeTerms.md) |  | [optional] 
**ap_payee_types** | [**GetVendorPickListsSuccessResponseResultApPayeeTypes**](GetVendorPickListsSuccessResponseResultApPayeeTypes.md) |  | [optional] 
**ap_payee_status_types** | [**GetVendorPickListsSuccessResponseResultApPayeeStatusTypes**](GetVendorPickListsSuccessResponseResultApPayeeStatusTypes.md) |  | [optional] 
**form1099_types** | [**GetVendorPickListsSuccessResponseResultForm1099Types**](GetVendorPickListsSuccessResponseResultForm1099Types.md) |  | [optional] 
**form1099_box_types** | [**GetVendorPickListsSuccessResponseResultForm1099BoxTypes**](GetVendorPickListsSuccessResponseResultForm1099BoxTypes.md) |  | [optional] 
**ap_remittance_types** | [**GetVendorPickListsSuccessResponseResultApRemittanceTypes**](GetVendorPickListsSuccessResponseResultApRemittanceTypes.md) |  | [optional] 
**utility_bill_receipt_types** | [**GetVendorPickListsSuccessResponseResultUtilityBillReceiptTypes**](GetVendorPickListsSuccessResponseResultUtilityBillReceiptTypes.md) |  | [optional] 
**bank_account_types** | [**GetVendorPickListsSuccessResponseResultBankAccountTypes**](GetVendorPickListsSuccessResponseResultBankAccountTypes.md) |  | [optional] 
**compliance_statuses** | [**GetVendorPickListsSuccessResponseResultComplianceStatuses**](GetVendorPickListsSuccessResponseResultComplianceStatuses.md) |  | [optional] 
**routing_tags** | [**GetVendorPickListsSuccessResponseResultRoutingTags**](GetVendorPickListsSuccessResponseResultRoutingTags.md) |  | [optional] 
**units_of_measure** | [**GetVendorPickListsSuccessResponseResultUnitsOfMeasure**](GetVendorPickListsSuccessResponseResultUnitsOfMeasure.md) |  | [optional] 
**policies** | [**GetVendorPickListsSuccessResponseResultPolicies**](GetVendorPickListsSuccessResponseResultPolicies.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_vendor_pick_lists_success_response_result import GetVendorPickListsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorPickListsSuccessResponseResult from a JSON string
get_vendor_pick_lists_success_response_result_instance = GetVendorPickListsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetVendorPickListsSuccessResponseResult.to_json())

# convert the object into a dict
get_vendor_pick_lists_success_response_result_dict = get_vendor_pick_lists_success_response_result_instance.to_dict()
# create an instance of GetVendorPickListsSuccessResponseResult from a dict
get_vendor_pick_lists_success_response_result_from_dict = GetVendorPickListsSuccessResponseResult.from_dict(get_vendor_pick_lists_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


