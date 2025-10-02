# UpdateCustomersSuccessResponseResultCustomersCustomerInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | The unique identifier for the customer node. | 
**reference_id** | **str** | The reference ID of the customer. | 
**status** | **str** | The status of the customer update request. | 
**message** | **str** | The message indicating the result of the customer update. | 

## Example

```python
from openapi_client.models.update_customers_success_response_result_customers_customer_inner import UpdateCustomersSuccessResponseResultCustomersCustomerInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomersSuccessResponseResultCustomersCustomerInner from a JSON string
update_customers_success_response_result_customers_customer_inner_instance = UpdateCustomersSuccessResponseResultCustomersCustomerInner.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomersSuccessResponseResultCustomersCustomerInner.to_json())

# convert the object into a dict
update_customers_success_response_result_customers_customer_inner_dict = update_customers_success_response_result_customers_customer_inner_instance.to_dict()
# create an instance of UpdateCustomersSuccessResponseResultCustomersCustomerInner from a dict
update_customers_success_response_result_customers_customer_inner_from_dict = UpdateCustomersSuccessResponseResultCustomersCustomerInner.from_dict(update_customers_success_response_result_customers_customer_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


