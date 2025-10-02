# GetFinancialPickListR2SuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_group_types** | [**GetFinancialPickListR2SuccessResponseResultGlGroupTypes**](GetFinancialPickListR2SuccessResponseResultGlGroupTypes.md) |  | 
**gl_tree_types** | [**GetFinancialPickListR2SuccessResponseResultGlTreeTypes**](GetFinancialPickListR2SuccessResponseResultGlTreeTypes.md) |  | 
**gl_account_types** | [**GetFinancialPickListR2SuccessResponseResultGlAccountTypes**](GetFinancialPickListR2SuccessResponseResultGlAccountTypes.md) |  | 
**gl_books** | [**GetFinancialPickListR2SuccessResponseResultGlBooks**](GetFinancialPickListR2SuccessResponseResultGlBooks.md) |  | 
**gl_branch_types** | [**GetFinancialPickListR2SuccessResponseResultGlBranchTypes**](GetFinancialPickListR2SuccessResponseResultGlBranchTypes.md) |  | 
**gl_export_batch_types** | [**GetFinancialPickListR2SuccessResponseResultGlExportBatchTypes**](GetFinancialPickListR2SuccessResponseResultGlExportBatchTypes.md) |  | 
**gl_header_status_types** | [**GetFinancialPickListR2SuccessResponseResultGlHeaderStatusTypes**](GetFinancialPickListR2SuccessResponseResultGlHeaderStatusTypes.md) |  | 
**gl_header_types** | [**GetFinancialPickListR2SuccessResponseResultGlHeaderTypes**](GetFinancialPickListR2SuccessResponseResultGlHeaderTypes.md) |  | 
**gl_ledger_types** | [**GetFinancialPickListR2SuccessResponseResultGlLedgerTypes**](GetFinancialPickListR2SuccessResponseResultGlLedgerTypes.md) |  | 
**gl_reconciliation_status_types** | [**GetFinancialPickListR2SuccessResponseResultGlReconciliationStatusTypes**](GetFinancialPickListR2SuccessResponseResultGlReconciliationStatusTypes.md) |  | 
**gl_transaction_types** | [**GetFinancialPickListR2SuccessResponseResultGlTransactionTypes**](GetFinancialPickListR2SuccessResponseResultGlTransactionTypes.md) |  | 
**budget_status_type_ids** | [**GetFinancialPickListR2SuccessResponseResultBudgetStatusTypeIds**](GetFinancialPickListR2SuccessResponseResultBudgetStatusTypeIds.md) |  | 
**owners** | [**GetFinancialPickListR2SuccessResponseResultOwners**](GetFinancialPickListR2SuccessResponseResultOwners.md) |  | 
**ledger_ids** | [**GetFinancialPickListR2SuccessResponseResultLedgerIds**](GetFinancialPickListR2SuccessResponseResultLedgerIds.md) |  | 

## Example

```python
from entrata_api_client.models.get_financial_pick_list_r2_success_response_result import GetFinancialPickListR2SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetFinancialPickListR2SuccessResponseResult from a JSON string
get_financial_pick_list_r2_success_response_result_instance = GetFinancialPickListR2SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetFinancialPickListR2SuccessResponseResult.to_json())

# convert the object into a dict
get_financial_pick_list_r2_success_response_result_dict = get_financial_pick_list_r2_success_response_result_instance.to_dict()
# create an instance of GetFinancialPickListR2SuccessResponseResult from a dict
get_financial_pick_list_r2_success_response_result_from_dict = GetFinancialPickListR2SuccessResponseResult.from_dict(get_financial_pick_list_r2_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


