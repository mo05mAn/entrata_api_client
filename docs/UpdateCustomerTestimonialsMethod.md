# UpdateCustomerTestimonialsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateCustomerTestimonialsMethodParams**](UpdateCustomerTestimonialsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_customer_testimonials_method import UpdateCustomerTestimonialsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomerTestimonialsMethod from a JSON string
update_customer_testimonials_method_instance = UpdateCustomerTestimonialsMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomerTestimonialsMethod.to_json())

# convert the object into a dict
update_customer_testimonials_method_dict = update_customer_testimonials_method_instance.to_dict()
# create an instance of UpdateCustomerTestimonialsMethod from a dict
update_customer_testimonials_method_from_dict = UpdateCustomerTestimonialsMethod.from_dict(update_customer_testimonials_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


