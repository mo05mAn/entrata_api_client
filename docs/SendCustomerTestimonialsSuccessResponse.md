# SendCustomerTestimonialsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**result** | [**SendCustomerTestimonialsSuccessResponseResult**](SendCustomerTestimonialsSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.send_customer_testimonials_success_response import SendCustomerTestimonialsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SendCustomerTestimonialsSuccessResponse from a JSON string
send_customer_testimonials_success_response_instance = SendCustomerTestimonialsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SendCustomerTestimonialsSuccessResponse.to_json())

# convert the object into a dict
send_customer_testimonials_success_response_dict = send_customer_testimonials_success_response_instance.to_dict()
# create an instance of SendCustomerTestimonialsSuccessResponse from a dict
send_customer_testimonials_success_response_from_dict = SendCustomerTestimonialsSuccessResponse.from_dict(send_customer_testimonials_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


