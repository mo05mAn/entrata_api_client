# GetBankAccountsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bank_accounts** | [**GetBankAccountsSuccessResponseResultBankAccounts**](GetBankAccountsSuccessResponseResultBankAccounts.md) |  | 

## Example

```python
from openapi_client.models.get_bank_accounts_success_response_result import GetBankAccountsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetBankAccountsSuccessResponseResult from a JSON string
get_bank_accounts_success_response_result_instance = GetBankAccountsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetBankAccountsSuccessResponseResult.to_json())

# convert the object into a dict
get_bank_accounts_success_response_result_dict = get_bank_accounts_success_response_result_instance.to_dict()
# create an instance of GetBankAccountsSuccessResponseResult from a dict
get_bank_accounts_success_response_result_from_dict = GetBankAccountsSuccessResponseResult.from_dict(get_bank_accounts_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


