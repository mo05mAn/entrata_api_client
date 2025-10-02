# GetBankAccounts


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetBankAccountsMethod**](GetBankAccountsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_bank_accounts import GetBankAccounts

# TODO update the JSON string below
json = "{}"
# create an instance of GetBankAccounts from a JSON string
get_bank_accounts_instance = GetBankAccounts.from_json(json)
# print the JSON string representation of the object
print(GetBankAccounts.to_json())

# convert the object into a dict
get_bank_accounts_dict = get_bank_accounts_instance.to_dict()
# create an instance of GetBankAccounts from a dict
get_bank_accounts_from_dict = GetBankAccounts.from_dict(get_bank_accounts_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


