# GetBankAccountsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**bank_account_type_id** | **int** | This is an optional field. This field accepts single value. Bank Account Type Identification Number | [optional] 
**is_credit_card_account** | **int** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from openapi_client.models.get_bank_accounts_method_params import GetBankAccountsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetBankAccountsMethodParams from a JSON string
get_bank_accounts_method_params_instance = GetBankAccountsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetBankAccountsMethodParams.to_json())

# convert the object into a dict
get_bank_accounts_method_params_dict = get_bank_accounts_method_params_instance.to_dict()
# create an instance of GetBankAccountsMethodParams from a dict
get_bank_accounts_method_params_from_dict = GetBankAccountsMethodParams.from_dict(get_bank_accounts_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


