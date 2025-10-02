# GetCustomerTestimonialsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **int** | The unique identifier for the request | 
**result** | [**GetCustomerTestimonialsSuccessResponseResult**](GetCustomerTestimonialsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.get_customer_testimonials_success_response import GetCustomerTestimonialsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomerTestimonialsSuccessResponse from a JSON string
get_customer_testimonials_success_response_instance = GetCustomerTestimonialsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetCustomerTestimonialsSuccessResponse.to_json())

# convert the object into a dict
get_customer_testimonials_success_response_dict = get_customer_testimonials_success_response_instance.to_dict()
# create an instance of GetCustomerTestimonialsSuccessResponse from a dict
get_customer_testimonials_success_response_from_dict = GetCustomerTestimonialsSuccessResponse.from_dict(get_customer_testimonials_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


