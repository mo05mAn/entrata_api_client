# GetCustomerTestimonialsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetCustomerTestimonialsMethodParams**](GetCustomerTestimonialsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_customer_testimonials_method import GetCustomerTestimonialsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomerTestimonialsMethod from a JSON string
get_customer_testimonials_method_instance = GetCustomerTestimonialsMethod.from_json(json)
# print the JSON string representation of the object
print(GetCustomerTestimonialsMethod.to_json())

# convert the object into a dict
get_customer_testimonials_method_dict = get_customer_testimonials_method_instance.to_dict()
# create an instance of GetCustomerTestimonialsMethod from a dict
get_customer_testimonials_method_from_dict = GetCustomerTestimonialsMethod.from_dict(get_customer_testimonials_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


