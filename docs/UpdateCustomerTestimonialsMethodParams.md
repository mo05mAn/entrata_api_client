# UpdateCustomerTestimonialsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**transmission_vendor_id** | **int** | This is a required field. This field accepts single value. | 
**testimonial_id** | **int** | This is an optional field. This field accepts single value. | [optional] 
**is_published** | **bool** | This is a required field. This field accepts single value. | 

## Example

```python
from openapi_client.models.update_customer_testimonials_method_params import UpdateCustomerTestimonialsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomerTestimonialsMethodParams from a JSON string
update_customer_testimonials_method_params_instance = UpdateCustomerTestimonialsMethodParams.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomerTestimonialsMethodParams.to_json())

# convert the object into a dict
update_customer_testimonials_method_params_dict = update_customer_testimonials_method_params_instance.to_dict()
# create an instance of UpdateCustomerTestimonialsMethodParams from a dict
update_customer_testimonials_method_params_from_dict = UpdateCustomerTestimonialsMethodParams.from_dict(update_customer_testimonials_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


