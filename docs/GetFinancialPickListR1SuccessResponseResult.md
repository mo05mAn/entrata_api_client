# GetFinancialPickListR1SuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**gl_group_types** | [**GetFinancialPickListR1SuccessResponseResultGlGroupTypes**](GetFinancialPickListR1SuccessResponseResultGlGroupTypes.md) |  | 
**gl_tree_types** | [**GetFinancialPickListR1SuccessResponseResultGlTreeTypes**](GetFinancialPickListR1SuccessResponseResultGlTreeTypes.md) |  | 
**gl_account_types** | [**GetFinancialPickListR1SuccessResponseResultGlAccountTypes**](GetFinancialPickListR1SuccessResponseResultGlAccountTypes.md) |  | 
**gl_books** | [**GetFinancialPickListR1SuccessResponseResultGlBooks**](GetFinancialPickListR1SuccessResponseResultGlBooks.md) |  | 
**gl_branch_types** | [**GetFinancialPickListR1SuccessResponseResultGlBranchTypes**](GetFinancialPickListR1SuccessResponseResultGlBranchTypes.md) |  | 
**gl_export_batch_types** | [**GetFinancialPickListR1SuccessResponseResultGlExportBatchTypes**](GetFinancialPickListR1SuccessResponseResultGlExportBatchTypes.md) |  | 
**gl_header_status_types** | [**GetFinancialPickListR1SuccessResponseResultGlHeaderStatusTypes**](GetFinancialPickListR1SuccessResponseResultGlHeaderStatusTypes.md) |  | 
**gl_header_types** | [**GetFinancialPickListR1SuccessResponseResultGlHeaderTypes**](GetFinancialPickListR1SuccessResponseResultGlHeaderTypes.md) |  | 
**gl_ledger_types** | [**GetFinancialPickListR1SuccessResponseResultGlLedgerTypes**](GetFinancialPickListR1SuccessResponseResultGlLedgerTypes.md) |  | 
**gl_reconciliation_status_types** | [**GetFinancialPickListR1SuccessResponseResultGlReconciliationStatusTypes**](GetFinancialPickListR1SuccessResponseResultGlReconciliationStatusTypes.md) |  | 
**gl_transaction_types** | [**GetFinancialPickListR1SuccessResponseResultGlTransactionTypes**](GetFinancialPickListR1SuccessResponseResultGlTransactionTypes.md) |  | 
**budgets** | [**GetFinancialPickListR1SuccessResponseResultBudgets**](GetFinancialPickListR1SuccessResponseResultBudgets.md) |  | 
**ledger_ids** | [**GetFinancialPickListR1SuccessResponseResultLedgerIds**](GetFinancialPickListR1SuccessResponseResultLedgerIds.md) |  | 

## Example

```python
from entrata_api_client.models.get_financial_pick_list_r1_success_response_result import GetFinancialPickListR1SuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetFinancialPickListR1SuccessResponseResult from a JSON string
get_financial_pick_list_r1_success_response_result_instance = GetFinancialPickListR1SuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetFinancialPickListR1SuccessResponseResult.to_json())

# convert the object into a dict
get_financial_pick_list_r1_success_response_result_dict = get_financial_pick_list_r1_success_response_result_instance.to_dict()
# create an instance of GetFinancialPickListR1SuccessResponseResult from a dict
get_financial_pick_list_r1_success_response_result_from_dict = GetFinancialPickListR1SuccessResponseResult.from_dict(get_financial_pick_list_r1_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


