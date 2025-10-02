# GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_payment_id** | **int** | The ID of the AR payment. | [optional] 
**property_name** | **str** | The name of the property associated with the payment. | [optional] 
**customer_id** | **int** | The ID of the customer making the payment. | [optional] 
**customer_first_name** | **str** | The first name of the customer. | [optional] 
**customer_last_name** | **str** | The last name of the customer. | [optional] 
**unit_number** | **int** | The unit number associated with the property. | [optional] 
**email_address** | **str** | The email address of the customer. | [optional] 
**payment_amount** | **int** | The amount of the payment. | [optional] 
**payment_date** | **str** | The date when the payment was made. | [optional] 
**payment_type** | **str** | The method of payment used. | [optional] 
**payment_status** | **str** | The status of the payment. | [optional] 
**external_id** | **str** | Customer&#39;s secondary number/external identifier. | [optional] 
**street_line1** | **str** | First line of billing street address. | [optional] 
**street_line2** | **str** | Second line of billing street address. | [optional] 
**street_line3** | **str** | Third line of billing street address. | [optional] 
**city** | **str** | Billing city. | [optional] 
**state_code** | **str** | Billing state code. | [optional] 
**postal_code** | **str** | Billing postal/zip code. | [optional] 
**phone_number** | **str** | Customer&#39;s phone number (processed to remove country code). | [optional] 
**currency_code** | **str** | Currency code for the payment based on property. | [optional] 
**captured_on** | **str** | Date/time when payment was captured (truncated to 16 characters). | [optional] 
**distribute_on** | **str** | Date/time when payment was distributed (truncated to 16 characters). | [optional] 
**returned_on** | **str** | Date/time when payment was returned (truncated to 16 characters). | [optional] 
**ar_allocations** | [**GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocations**](GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInnerArAllocations.md) |  | 

## Example

```python
from openapi_client.models.get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner import GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInner from a JSON string
get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_instance = GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInner.from_json(json)
# print the JSON string representation of the object
print(GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInner.to_json())

# convert the object into a dict
get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_dict = get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_instance.to_dict()
# create an instance of GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInner from a dict
get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_from_dict = GetArPaymentsSuccessResponseResponseResultArPaymentsArPaymentInner.from_dict(get_ar_payments_success_response_response_result_ar_payments_ar_payment_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


