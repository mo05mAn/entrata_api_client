# GetMitsLeaseArTransactionsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. PropertyId | 
**lease_id** | **int** | This is an optional field. This field accepts single value. leaseId | [optional] 
**lease_status_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. If provided API returns data as per leaseStatusTypeIds, otherwise if N ot passed or passed as NULL/blank, returns all leases except canceled. | [optional] 
**ar_code_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. arCodeIds | [optional] 
**show_full_ledger** | **int** | This is an optional field. This field accepts single value. This is parameter allows you to pull full ledger history. By default i t only returns open ledger items. | [optional] 
**include_reversals** | **int** | This is an optional field. This field accepts single value. This parameter return reversal transactions in API response. Also to i nclude the reversal transaction in response \&quot;showFullLedger\&quot; must be true(1). | [optional] 
**resident_friendly_mode** | **int** | This is an optional field. This field accepts single value. This is parameter allows you to pull ledger history as displayed under resident portal | [optional] 
**include_other_income_leases** | **int** | This is an optional field. This field accepts single value. This parameter is used to get the Other income leases in the response. | [optional] 
**include_payments_only** | **int** | This is an optional field. This field accepts single value. This parameter is used to retrieve payments transactions in the response | [optional] 
**transaction_from_date** | **date** | This is an optional field. This field accepts single value. transactionFromDate | [optional] 
**transaction_to_date** | **date** | This is an optional field. This field accepts single value. transactionToDate | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_lease_ar_transactions_method_params import GetMitsLeaseArTransactionsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeaseArTransactionsMethodParams from a JSON string
get_mits_lease_ar_transactions_method_params_instance = GetMitsLeaseArTransactionsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeaseArTransactionsMethodParams.to_json())

# convert the object into a dict
get_mits_lease_ar_transactions_method_params_dict = get_mits_lease_ar_transactions_method_params_instance.to_dict()
# create an instance of GetMitsLeaseArTransactionsMethodParams from a dict
get_mits_lease_ar_transactions_method_params_from_dict = GetMitsLeaseArTransactionsMethodParams.from_dict(get_mits_lease_ar_transactions_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


