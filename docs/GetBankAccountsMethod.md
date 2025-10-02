# GetBankAccountsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetBankAccountsMethodParams**](GetBankAccountsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_bank_accounts_method import GetBankAccountsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetBankAccountsMethod from a JSON string
get_bank_accounts_method_instance = GetBankAccountsMethod.from_json(json)
# print the JSON string representation of the object
print(GetBankAccountsMethod.to_json())

# convert the object into a dict
get_bank_accounts_method_dict = get_bank_accounts_method_instance.to_dict()
# create an instance of GetBankAccountsMethod from a dict
get_bank_accounts_method_from_dict = GetBankAccountsMethod.from_dict(get_bank_accounts_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


