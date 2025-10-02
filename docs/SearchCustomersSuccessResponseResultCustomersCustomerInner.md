# SearchCustomersSuccessResponseResultCustomersCustomerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the customer | 
**name_prefix** | **str** | The name prefix of the customer | 
**first_name** | **str** | The first name of the customer | 
**middle_name** | **str** | The middle name of the customer | [optional] 
**last_name** | **str** | The last name of the customer | 
**email** | **str** | The email address of the customer | 
**unit_number** | **str** | The unit number of the customer&#39;s address | 
**building_name** | **str** | The name of the building where the customer resides | 
**address** | **str** | The street address of the customer | 
**city** | **str** | The city where the customer resides | 
**state** | **str** | The state where the customer resides | 
**postal_code** | **str** | The postal code for the customer&#39;s address | 
**is_active_bankruptcy** | **bool** | The Bankruptcy status of customer . | [optional] 
**bankruptcy_date** | **str** | The Bankruptcy date of customer. | [optional] 
**bankruptcy_note** | **str** | XYZ | [optional] 

## Example

```python
from entrata_api_client.models.search_customers_success_response_result_customers_customer_inner import SearchCustomersSuccessResponseResultCustomersCustomerInner

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCustomersSuccessResponseResultCustomersCustomerInner from a JSON string
search_customers_success_response_result_customers_customer_inner_instance = SearchCustomersSuccessResponseResultCustomersCustomerInner.from_json(json)
# print the JSON string representation of the object
print(SearchCustomersSuccessResponseResultCustomersCustomerInner.to_json())

# convert the object into a dict
search_customers_success_response_result_customers_customer_inner_dict = search_customers_success_response_result_customers_customer_inner_instance.to_dict()
# create an instance of SearchCustomersSuccessResponseResultCustomersCustomerInner from a dict
search_customers_success_response_result_customers_customer_inner_from_dict = SearchCustomersSuccessResponseResultCustomersCustomerInner.from_dict(search_customers_success_response_result_customers_customer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


