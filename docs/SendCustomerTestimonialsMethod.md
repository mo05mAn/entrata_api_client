# SendCustomerTestimonialsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendCustomerTestimonialsMethodParams**](SendCustomerTestimonialsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_customer_testimonials_method import SendCustomerTestimonialsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendCustomerTestimonialsMethod from a JSON string
send_customer_testimonials_method_instance = SendCustomerTestimonialsMethod.from_json(json)
# print the JSON string representation of the object
print(SendCustomerTestimonialsMethod.to_json())

# convert the object into a dict
send_customer_testimonials_method_dict = send_customer_testimonials_method_instance.to_dict()
# create an instance of SendCustomerTestimonialsMethod from a dict
send_customer_testimonials_method_from_dict = SendCustomerTestimonialsMethod.from_dict(send_customer_testimonials_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


