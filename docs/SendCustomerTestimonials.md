# SendCustomerTestimonials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendCustomerTestimonialsMethod**](SendCustomerTestimonialsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_customer_testimonials import SendCustomerTestimonials

# TODO update the JSON string below
json = "{}"
# create an instance of SendCustomerTestimonials from a JSON string
send_customer_testimonials_instance = SendCustomerTestimonials.from_json(json)
# print the JSON string representation of the object
print(SendCustomerTestimonials.to_json())

# convert the object into a dict
send_customer_testimonials_dict = send_customer_testimonials_instance.to_dict()
# create an instance of SendCustomerTestimonials from a dict
send_customer_testimonials_from_dict = SendCustomerTestimonials.from_dict(send_customer_testimonials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


