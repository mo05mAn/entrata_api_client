# GetCustomerTestimonials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetCustomerTestimonialsMethod**](GetCustomerTestimonialsMethod.md) |  | 

## Example

```python
from openapi_client.models.get_customer_testimonials import GetCustomerTestimonials

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomerTestimonials from a JSON string
get_customer_testimonials_instance = GetCustomerTestimonials.from_json(json)
# print the JSON string representation of the object
print(GetCustomerTestimonials.to_json())

# convert the object into a dict
get_customer_testimonials_dict = get_customer_testimonials_instance.to_dict()
# create an instance of GetCustomerTestimonials from a dict
get_customer_testimonials_from_dict = GetCustomerTestimonials.from_dict(get_customer_testimonials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


