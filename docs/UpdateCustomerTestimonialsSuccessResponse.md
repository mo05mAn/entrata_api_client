# UpdateCustomerTestimonialsSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request. | 
**code** | **int** | The response code indicating the status of the request. | 
**result** | [**UpdateCustomerTestimonialsSuccessResponseResult**](UpdateCustomerTestimonialsSuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.update_customer_testimonials_success_response import UpdateCustomerTestimonialsSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomerTestimonialsSuccessResponse from a JSON string
update_customer_testimonials_success_response_instance = UpdateCustomerTestimonialsSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomerTestimonialsSuccessResponse.to_json())

# convert the object into a dict
update_customer_testimonials_success_response_dict = update_customer_testimonials_success_response_instance.to_dict()
# create an instance of UpdateCustomerTestimonialsSuccessResponse from a dict
update_customer_testimonials_success_response_from_dict = UpdateCustomerTestimonialsSuccessResponse.from_dict(update_customer_testimonials_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


