# VoidApPaymentsSuccessResponseResultApPaymentsApPaymentInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | The node identifier of the payment. | [optional] 
**status** | **str** | Status of the payment void operation. | [optional] 
**message** | **str** | Message indicating the result of the payment void. | [optional] 
**payment_id** | **str** | The unique identifier for the payment. | [optional] 
**payment_number** | **str** | The payment number. | [optional] 

## Example

```python
from entrata_api_client.models.void_ap_payments_success_response_result_ap_payments_ap_payment_inner import VoidApPaymentsSuccessResponseResultApPaymentsApPaymentInner

# TODO update the JSON string below
json = "{}"
# create an instance of VoidApPaymentsSuccessResponseResultApPaymentsApPaymentInner from a JSON string
void_ap_payments_success_response_result_ap_payments_ap_payment_inner_instance = VoidApPaymentsSuccessResponseResultApPaymentsApPaymentInner.from_json(json)
# print the JSON string representation of the object
print(VoidApPaymentsSuccessResponseResultApPaymentsApPaymentInner.to_json())

# convert the object into a dict
void_ap_payments_success_response_result_ap_payments_ap_payment_inner_dict = void_ap_payments_success_response_result_ap_payments_ap_payment_inner_instance.to_dict()
# create an instance of VoidApPaymentsSuccessResponseResultApPaymentsApPaymentInner from a dict
void_ap_payments_success_response_result_ap_payments_ap_payment_inner_from_dict = VoidApPaymentsSuccessResponseResultApPaymentsApPaymentInner.from_dict(void_ap_payments_success_response_result_ap_payments_ap_payment_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


