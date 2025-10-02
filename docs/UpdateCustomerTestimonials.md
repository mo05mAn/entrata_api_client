# UpdateCustomerTestimonials


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateCustomerTestimonialsMethod**](UpdateCustomerTestimonialsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.update_customer_testimonials import UpdateCustomerTestimonials

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomerTestimonials from a JSON string
update_customer_testimonials_instance = UpdateCustomerTestimonials.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomerTestimonials.to_json())

# convert the object into a dict
update_customer_testimonials_dict = update_customer_testimonials_instance.to_dict()
# create an instance of UpdateCustomerTestimonials from a dict
update_customer_testimonials_from_dict = UpdateCustomerTestimonials.from_dict(update_customer_testimonials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


