# VoidApPaymentsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ap_payments** | [**VoidApPaymentsSuccessResponseResultApPayments**](VoidApPaymentsSuccessResponseResultApPayments.md) |  | [optional] 

## Example

```python
from openapi_client.models.void_ap_payments_success_response_result import VoidApPaymentsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of VoidApPaymentsSuccessResponseResult from a JSON string
void_ap_payments_success_response_result_instance = VoidApPaymentsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(VoidApPaymentsSuccessResponseResult.to_json())

# convert the object into a dict
void_ap_payments_success_response_result_dict = void_ap_payments_success_response_result_instance.to_dict()
# create an instance of VoidApPaymentsSuccessResponseResult from a dict
void_ap_payments_success_response_result_from_dict = VoidApPaymentsSuccessResponseResult.from_dict(void_ap_payments_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


