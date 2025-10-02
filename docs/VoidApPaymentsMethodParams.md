# VoidApPaymentsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**payment_id** | **int** | This is an optional field. This field accepts single value. This is a conditional mandatory node. If the value for paymentNumber, paymentBankAccountId, paymenttypeId, paymentAmount are not provided. | [optional] 
**payment_number** | **str** | This is an optional field. This field accepts single value. This is a conditional mandatory node. If the value for paymentId is no t provided then this node is required. | [optional] 
**payment_bank_account_id** | **int** | This is an optional field. This field accepts single value. This is a conditional mandatory node. If the value of paymentId is not provided then this node is required. | [optional] 
**payment_type_id** | **int** | This is an optional field. This field accepts single value. This is a conditional mandatory node. If the value of paymentId is not provided then this node is required. | [optional] 
**payment_amount** | **int** | This is an optional field. This field accepts single value. This is a conditional mandatory node. If the value of paymentId is not provided then this node is required. | [optional] 
**void_date** | **date** | This is a required field. This field accepts single value. Supported date format: MM/DD/YYY, M/D/YYYY, YYYY-MM-DD. | 
**post_month** | **date** | This is a required field. This field accepts single value. Supported Format: MM/YYYY | 
**note** | **str** | This is a required field. This field accepts single value. Memo for the payment | 

## Example

```python
from openapi_client.models.void_ap_payments_method_params import VoidApPaymentsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of VoidApPaymentsMethodParams from a JSON string
void_ap_payments_method_params_instance = VoidApPaymentsMethodParams.from_json(json)
# print the JSON string representation of the object
print(VoidApPaymentsMethodParams.to_json())

# convert the object into a dict
void_ap_payments_method_params_dict = void_ap_payments_method_params_instance.to_dict()
# create an instance of VoidApPaymentsMethodParams from a dict
void_ap_payments_method_params_from_dict = VoidApPaymentsMethodParams.from_dict(void_ap_payments_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


