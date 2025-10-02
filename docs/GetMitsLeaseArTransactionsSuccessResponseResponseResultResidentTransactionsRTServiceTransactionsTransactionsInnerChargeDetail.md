# GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetail


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**description** | **str** | Description of the charge | 
**transaction_date** | **str** | Transaction date | 
**service_to_date** | **str** | Service to date | [optional] 
**transaction_id** | **int** | Transaction ID | 
**charge_code** | **str** | Charge code | 
**supplemental_id** | [**GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetailSupplementalID**](GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetailSupplementalID.md) |  | [optional] 
**balance_due** | **str** | Balance due | 
**amount** | **str** | Charge amount | 
**reversal_tran_id** | **str** | Reversal transaction ID | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_lease_ar_transactions_success_response_response_result_resident_transactions_rt_service_transactions_transactions_inner_charge_detail import GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetail

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetail from a JSON string
get_mits_lease_ar_transactions_success_response_response_result_resident_transactions_rt_service_transactions_transactions_inner_charge_detail_instance = GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetail.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetail.to_json())

# convert the object into a dict
get_mits_lease_ar_transactions_success_response_response_result_resident_transactions_rt_service_transactions_transactions_inner_charge_detail_dict = get_mits_lease_ar_transactions_success_response_response_result_resident_transactions_rt_service_transactions_transactions_inner_charge_detail_instance.to_dict()
# create an instance of GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetail from a dict
get_mits_lease_ar_transactions_success_response_response_result_resident_transactions_rt_service_transactions_transactions_inner_charge_detail_from_dict = GetMitsLeaseArTransactionsSuccessResponseResponseResultResidentTransactionsRTServiceTransactionsTransactionsInnerChargeDetail.from_dict(get_mits_lease_ar_transactions_success_response_response_result_resident_transactions_rt_service_transactions_transactions_inner_charge_detail_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


