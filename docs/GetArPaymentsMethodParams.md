# GetArPaymentsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ar_payment_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. Comma separated ar payment ids. | [optional] 
**payment_status_type_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. Comma separated payment status type ids. | [optional] 
**from_date** | **date** | This is an optional field. This field accepts single value. From date. | [optional] 
**to_date** | **date** | This is an optional field. This field accepts single value. To date | [optional] 
**is_include_allocations** | **int** | This is an optional field. This field accepts single value. This node should include allocations details of payment | [optional] 

## Example

```python
from entrata_api_client.models.get_ar_payments_method_params import GetArPaymentsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetArPaymentsMethodParams from a JSON string
get_ar_payments_method_params_instance = GetArPaymentsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetArPaymentsMethodParams.to_json())

# convert the object into a dict
get_ar_payments_method_params_dict = get_ar_payments_method_params_instance.to_dict()
# create an instance of GetArPaymentsMethodParams from a dict
get_ar_payments_method_params_from_dict = GetArPaymentsMethodParams.from_dict(get_ar_payments_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


