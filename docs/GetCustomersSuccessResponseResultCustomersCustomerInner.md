# GetCustomersSuccessResponseResultCustomersCustomerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease_id** | [**List[GetCustomersSuccessResponseResultCustomersCustomerInnerLeaseIdInner]**](GetCustomersSuccessResponseResultCustomersCustomerInnerLeaseIdInner.md) |  | 
**first_name** | **str** | The first name of the customer | 
**last_name** | **str** | The last name of the customer | 
**unit_number** | **str** | The unit number of the customer | 
**building_name** | **str** | The name of the building | 
**address** | **str** | The primary address of the customer | 
**city** | **str** | City where the customer resides | 
**state** | **str** | State where the customer resides | 
**postal_code** | **str** | Postal code for the customer address | 
**email** | **str** | The email address of the customer | 
**phone_number** | **str** | The phone number of the customer | 
**terms_approved_date** | **str** | The date when the terms were approved | 
**customer_addresses** | [**GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddresses**](GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerAddresses.md) |  | [optional] 
**points_earned** | **str** | The points earned by the customer | 
**vehicles** | [**GetCustomersSuccessResponseResultCustomersCustomerInnerVehicles**](GetCustomersSuccessResponseResultCustomersCustomerInnerVehicles.md) |  | 
**customer_identification_values** | [**GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerIdentificationValues**](GetCustomersSuccessResponseResultCustomersCustomerInnerCustomerIdentificationValues.md) |  | 
**is_active_bankruptcy** | **bool** | The Bankruptcy status of customer . | [optional] 
**bankruptcy_date** | **str** | The Bankruptcy date of customer. | [optional] 
**bankruptcy_note** | **str** | XYZ | [optional] 
**attributes** | [**GetCustomersSuccessResponseResultCustomersCustomerInnerAttributes**](GetCustomersSuccessResponseResultCustomersCustomerInnerAttributes.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_customers_success_response_result_customers_customer_inner import GetCustomersSuccessResponseResultCustomersCustomerInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersSuccessResponseResultCustomersCustomerInner from a JSON string
get_customers_success_response_result_customers_customer_inner_instance = GetCustomersSuccessResponseResultCustomersCustomerInner.from_json(json)
# print the JSON string representation of the object
print(GetCustomersSuccessResponseResultCustomersCustomerInner.to_json())

# convert the object into a dict
get_customers_success_response_result_customers_customer_inner_dict = get_customers_success_response_result_customers_customer_inner_instance.to_dict()
# create an instance of GetCustomersSuccessResponseResultCustomersCustomerInner from a dict
get_customers_success_response_result_customers_customer_inner_from_dict = GetCustomersSuccessResponseResultCustomersCustomerInner.from_dict(get_customers_success_response_result_customers_customer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


