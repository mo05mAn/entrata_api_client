# GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocationsArAllocationInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_transaction_id** | **int** | The ID of the AR transaction. | 
**charge_code_id** | **int** | The ID of the charge code associated with the payment. | [optional] 
**charge_code_name** | **str** | The name of the charge code. | [optional] 
**allocation_date_time** | **str** | The date and time when the allocation was made. | [optional] 
**amount** | **int** | The amount allocated to this AR transaction. | [optional] 

## Example

```python
from openapi_client.models.get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_ar_allocations_ar_allocation_inner import GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocationsArAllocationInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocationsArAllocationInner from a JSON string
get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_ar_allocations_ar_allocation_inner_instance = GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocationsArAllocationInner.from_json(json)
# print the JSON string representation of the object
print(GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocationsArAllocationInner.to_json())

# convert the object into a dict
get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_ar_allocations_ar_allocation_inner_dict = get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_ar_allocations_ar_allocation_inner_instance.to_dict()
# create an instance of GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocationsArAllocationInner from a dict
get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_ar_allocations_ar_allocation_inner_from_dict = GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocationsArAllocationInner.from_dict(get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_ar_allocations_ar_allocation_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


