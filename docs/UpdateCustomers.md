# UpdateCustomers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateCustomersMethod**](UpdateCustomersMethod.md) |  | 

## Example

```python
from openapi_client.models.update_customers import UpdateCustomers

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomers from a JSON string
update_customers_instance = UpdateCustomers.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomers.to_json())

# convert the object into a dict
update_customers_dict = update_customers_instance.to_dict()
# create an instance of UpdateCustomers from a dict
update_customers_from_dict = UpdateCustomers.from_dict(update_customers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


