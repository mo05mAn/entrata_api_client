# VoidApPaymentsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**VoidApPaymentsMethodParams**](VoidApPaymentsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.void_ap_payments_method import VoidApPaymentsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of VoidApPaymentsMethod from a JSON string
void_ap_payments_method_instance = VoidApPaymentsMethod.from_json(json)
# print the JSON string representation of the object
print(VoidApPaymentsMethod.to_json())

# convert the object into a dict
void_ap_payments_method_dict = void_ap_payments_method_instance.to_dict()
# create an instance of VoidApPaymentsMethod from a dict
void_ap_payments_method_from_dict = VoidApPaymentsMethod.from_dict(void_ap_payments_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


