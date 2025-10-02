# GetCustomerTestimonialsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is an optional field. This field accepts single value. Property id | [optional] 
**is_approved** | **bool** |  | [optional] 
**from_date** | **date** | This is an optional field. This field accepts single value. This will fetch the testimonials from this date | [optional] 
**to_date** | **date** | This is an optional field. This field accepts single value. This will fetch the testimonials until this date | [optional] 

## Example

```python
from openapi_client.models.get_customer_testimonials_method_params import GetCustomerTestimonialsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomerTestimonialsMethodParams from a JSON string
get_customer_testimonials_method_params_instance = GetCustomerTestimonialsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetCustomerTestimonialsMethodParams.to_json())

# convert the object into a dict
get_customer_testimonials_method_params_dict = get_customer_testimonials_method_params_instance.to_dict()
# create an instance of GetCustomerTestimonialsMethodParams from a dict
get_customer_testimonials_method_params_from_dict = GetCustomerTestimonialsMethodParams.from_dict(get_customer_testimonials_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


