# VoidApPayments


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**VoidApPaymentsMethod**](VoidApPaymentsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.void_ap_payments import VoidApPayments

# TODO update the JSON string below
json = "{}"
# create an instance of VoidApPayments from a JSON string
void_ap_payments_instance = VoidApPayments.from_json(json)
# print the JSON string representation of the object
print(VoidApPayments.to_json())

# convert the object into a dict
void_ap_payments_dict = void_ap_payments_instance.to_dict()
# create an instance of VoidApPayments from a dict
void_ap_payments_from_dict = VoidApPayments.from_dict(void_ap_payments_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


