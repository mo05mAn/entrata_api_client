# GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccountsPropertyBankAccountInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the property bank account. | 
**property_id** | **str** | The property identifier associated with the property bank account. | 
**gl_account_id** | **str** | The general ledger account ID associated with the property. | 
**is_due_to_from** | **str** | Indicates if the account is due to/from a particular property. | 

## Example

```python
from openapi_client.models.get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_property_bank_accounts_property_bank_account_inner import GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccountsPropertyBankAccountInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccountsPropertyBankAccountInner from a JSON string
get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_property_bank_accounts_property_bank_account_inner_instance = GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccountsPropertyBankAccountInner.from_json(json)
# print the JSON string representation of the object
print(GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccountsPropertyBankAccountInner.to_json())

# convert the object into a dict
get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_property_bank_accounts_property_bank_account_inner_dict = get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_property_bank_accounts_property_bank_account_inner_instance.to_dict()
# create an instance of GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccountsPropertyBankAccountInner from a dict
get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_property_bank_accounts_property_bank_account_inner_from_dict = GetBankAccountsSuccessResponseResultBankAccountsBankAccountInnerPropertyBankAccountsPropertyBankAccountInner.from_dict(get_bank_accounts_success_response_result_bank_accounts_bank_account_inner_property_bank_accounts_property_bank_account_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


