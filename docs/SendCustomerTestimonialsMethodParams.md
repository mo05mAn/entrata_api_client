# SendCustomerTestimonialsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customer_id** | **int** | This is an optional field. This field accepts single value. Child element of Testimonial. Customer Id. | [optional] 
**testimonial_type_id** | **int** | This is a required field. This field accepts single value. The following are valid testimonial type ids: 1 Resident testimonial 2 Employee testimonial 3 Client testimonial 4 Vacancy 5 Apartmentr atings.com 6 Yelp.com 7 atlanta.citysearch.com | 
**name** | **str** | This is an optional field. This field accepts single value. Child element of Testimonial. Name of a person who submitted the testi monial. | [optional] 
**title** | **str** | This is a required field. This field accepts single value. Child element of Testimonial. Title of testimonial. | 
**review** | **str** | This is a required field. This field accepts single value. Child element of Testimonial. Review content. | 
**recommend_to_friend** | **int** | This is an optional field. This field accepts single value. Child element of Testimonial. Do you recommend this property to any friend?. | [optional] 
**authorize_to_show_on_corporate_sites** | **bool** | This is a required field. This field accepts single value. Child element of Testimonial. Do you authorize property manager to dis play your testimonial on its portal and affiliate websites?. | 
**rating_type_id** | **int** | This is a required field. This field accepts single value. The following are valid testimonial rating types ids: 1 Parking 2 No ise 3 Grounds 5 Construction 6 Maintenance 7 Staff 8 Overall | 
**rating** | **int** | This is a required field. This field accepts single value. Child element of TestimonialRatings. Rating value. | 
**auto_approve_for_prospect_portal** | **int** | This is an optional field. This field accepts single value. Child element of Testimonial. Set to 1 if want to auto approve the tes timonial and post it on prospect portal. | [optional] 
**auto_approve_for_vacancy** | **int** | This is an optional field. This field accepts single value. Child element of Testimonial. Set to 1 if want to auto approve the tes timonial and post it on vacany.com | [optional] 
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**testimonial_datetime** | **date** | This is an optional field. This field accepts single value. Testimonial submission date. | [optional] 
**transmission_vendor_id** | **int** | This is an optional field. This field accepts single value. Transmission Vendor Id | [optional] 
**email** | **str** | This is an optional field. This field accepts single value. Email will be required if CustomerId is not provided. Child element of Testimonial. Email of a person who submitted the testimonial. | [optional] 
**property_response** | **str** | This is an optional field. This field accepts single value. The property&#x60;s response to the review. | [optional] 

## Example

```python
from entrata_api_client.models.send_customer_testimonials_method_params import SendCustomerTestimonialsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SendCustomerTestimonialsMethodParams from a JSON string
send_customer_testimonials_method_params_instance = SendCustomerTestimonialsMethodParams.from_json(json)
# print the JSON string representation of the object
print(SendCustomerTestimonialsMethodParams.to_json())

# convert the object into a dict
send_customer_testimonials_method_params_dict = send_customer_testimonials_method_params_instance.to_dict()
# create an instance of SendCustomerTestimonialsMethodParams from a dict
send_customer_testimonials_method_params_from_dict = SendCustomerTestimonialsMethodParams.from_dict(send_customer_testimonials_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


