# SendCustomerTestimonialsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**testimonials** | [**SendCustomerTestimonialsSuccessResponseResultTestimonials**](SendCustomerTestimonialsSuccessResponseResultTestimonials.md) |  | 

## Example

```python
from openapi_client.models.send_customer_testimonials_success_response_result import SendCustomerTestimonialsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendCustomerTestimonialsSuccessResponseResult from a JSON string
send_customer_testimonials_success_response_result_instance = SendCustomerTestimonialsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendCustomerTestimonialsSuccessResponseResult.to_json())

# convert the object into a dict
send_customer_testimonials_success_response_result_dict = send_customer_testimonials_success_response_result_instance.to_dict()
# create an instance of SendCustomerTestimonialsSuccessResponseResult from a dict
send_customer_testimonials_success_response_result_from_dict = SendCustomerTestimonialsSuccessResponseResult.from_dict(send_customer_testimonials_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


