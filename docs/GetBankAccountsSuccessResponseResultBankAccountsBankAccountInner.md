# GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the bank account. | 
**account_name** | **str** | The name of the bank account. | 
**bank_account_type_id** | **str** | The type ID of the bank account. | 
**property_bank_accounts** | [**GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccounts**](GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccounts.md) |  | 
**account_type** | **str** | The type of the bank account. | 
**check_bank_name** | **str** | The name of the bank associated with checks for the account. | 
**next_check_number** | **str** | The next check number to be issued for the account. | 

## Example

```python
from openapi_client.models.get_bank_accounts_success_response_result_bank_accounts_bank_account_inner import GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner from a JSON string
get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_instance = GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner.from_json(json)
# print the JSON string representation of the object
print(GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner.to_json())

# convert the object into a dict
get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_dict = get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_instance.to_dict()
# create an instance of GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner from a dict
get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_from_dict = GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner.from_dict(get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


