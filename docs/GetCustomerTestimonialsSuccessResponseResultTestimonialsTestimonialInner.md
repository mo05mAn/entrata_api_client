# GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the testimonial | 
**name** | **str** | Name of the person providing the testimonial | 
**title** | **str** | Title of the testimonial | 
**testimonial** | **str** | The actual testimonial content | 
**property_id** | **str** | The unique identifier for the property | 
**property_name** | **str** | The name of the property | 
**email_address** | **str** | Email address of the person providing the testimonial | 
**testimonial_datetime** | **str** | Date and time when the testimonial was created | 
**testimonial_type** | **str** | Type of testimonial | 
**is_recommended** | **str** | Whether the testimonial is a recommendation | 
**show_on_corporate_sites** | **str** | Whether the testimonial is shown on corporate sites | 
**vacancy_published** | **str** | Whether the vacancy is published | 
**prospect_portal_published** | **str** | Whether the testimonial is published on the prospect portal | 
**first_name** | **str** | First name of the person providing the testimonial | 
**last_name** | **str** | Last name of the person providing the testimonial | 
**testimonial_ratings** | [**GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInnerTestimonialRatings**](GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInnerTestimonialRatings.md) |  | 

## Example

```python
from entrata_api_client.models.get_customer_testimonials_success_response_result_testimonials_testimonial_inner import GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInner from a JSON string
get_customer_testimonials_success_response_result_testimonials_testimonial_inner_instance = GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInner.from_json(json)
# print the JSON string representation of the object
print(GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInner.to_json())

# convert the object into a dict
get_customer_testimonials_success_response_result_testimonials_testimonial_inner_dict = get_customer_testimonials_success_response_result_testimonials_testimonial_inner_instance.to_dict()
# create an instance of GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInner from a dict
get_customer_testimonials_success_response_result_testimonials_testimonial_inner_from_dict = GetCustomerTestimonialsSuccessResponseResultTestimonialsTestimonialInner.from_dict(get_customer_testimonials_success_response_result_testimonials_testimonial_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


