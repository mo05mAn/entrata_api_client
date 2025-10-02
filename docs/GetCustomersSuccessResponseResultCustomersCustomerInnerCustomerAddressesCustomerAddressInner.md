# GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**address** | **str** | Forwarding address | 
**city** | **str** | City of the forwarding address | 
**state** | **str** | State of the forwarding address | 
**postal_code** | **str** | Postal code of the forwarding address | 
**country** | **str** | Country of the forwarding address | 
**attributes** | [**GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInnerAttributes**](GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInnerAttributes.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_customers_success_response_result_customers_customer_inner_customer_addresses_customer_address_inner import GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInner from a JSON string
get_customers_success_response_result_customers_customer_inner_customer_addresses_customer_address_inner_instance = GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInner.from_json(json)
# print the JSON string representation of the object
print(GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInner.to_json())

# convert the object into a dict
get_customers_success_response_result_customers_customer_inner_customer_addresses_customer_address_inner_dict = get_customers_success_response_result_customers_customer_inner_customer_addresses_customer_address_inner_instance.to_dict()
# create an instance of GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInner from a dict
get_customers_success_response_result_customers_customer_inner_customer_addresses_customer_address_inner_from_dict = GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddressesCustomerAddressInner.from_dict(get_customers_success_response_result_customers_customer_inner_customer_addresses_customer_address_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


