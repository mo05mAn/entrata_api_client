# VoidApPaymentsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**result** | [**VoidApPaymentsSuccessResponseResult**](VoidApPaymentsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.void_ap_payments_success_response import VoidApPaymentsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of VoidApPaymentsSuccessResponse from a JSON string
void_ap_payments_success_response_instance = VoidApPaymentsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(VoidApPaymentsSuccessResponse.to_json())

# convert the object into a dict
void_ap_payments_success_response_dict = void_ap_payments_success_response_instance.to_dict()
# create an instance of VoidApPaymentsSuccessResponse from a dict
void_ap_payments_success_response_from_dict = VoidApPaymentsSuccessResponse.from_dict(void_ap_payments_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


