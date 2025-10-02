# UpdateCustomersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**UpdateCustomersMethodParams**](UpdateCustomersMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_customers_method import UpdateCustomersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCustomersMethod from a JSON string
update_customers_method_instance = UpdateCustomersMethod.from_json(json)
# print the JSON string representation of the object
print(UpdateCustomersMethod.to_json())

# convert the object into a dict
update_customers_method_dict = update_customers_method_instance.to_dict()
# create an instance of UpdateCustomersMethod from a dict
update_customers_method_from_dict = UpdateCustomersMethod.from_dict(update_customers_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


