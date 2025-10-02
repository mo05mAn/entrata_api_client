# GetBankAccountsSuccessResponseResultBankAccounts


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bank_account** | [**List[GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner]**](GetBankAccountsSuccessResponseResultBankAccountsBankAccountInner.md) | A list of bank accounts. | 

## Example

```python
from openapi_client.models.get_bank_accounts_success_response_result_bank_accounts import GetBankAccountsSuccessResponseResultBankAccounts

# TODO update the JSON string below
json = "{}"
# create an instance of GetBankAccountsSuccessResponseResultBankAccounts from a JSON string
get_bank_accounts_success_response_result_bank_accounts_instance = GetBankAccountsSuccessResponseResultBankAccounts.from_json(json)
# print the JSON string representation of the object
print(GetBankAccountsSuccessResponseResultBankAccounts.to_json())

# convert the object into a dict
get_bank_accounts_success_response_result_bank_accounts_dict = get_bank_accounts_success_response_result_bank_accounts_instance.to_dict()
# create an instance of GetBankAccountsSuccessResponseResultBankAccounts from a dict
get_bank_accounts_success_response_result_bank_accounts_from_dict = GetBankAccountsSuccessResponseResultBankAccounts.from_dict(get_bank_accounts_success_response_result_bank_accounts_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


