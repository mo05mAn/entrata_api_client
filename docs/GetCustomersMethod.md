# GetCustomersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetCustomersMethodParams**](GetCustomersMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_customers_method import GetCustomersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersMethod from a JSON string
get_customers_method_instance = GetCustomersMethod.from_json(json)
# print the JSON string representation of the object
print(GetCustomersMethod.to_json())

# convert the object into a dict
get_customers_method_dict = get_customers_method_instance.to_dict()
# create an instance of GetCustomersMethod from a dict
get_customers_method_from_dict = GetCustomersMethod.from_dict(get_customers_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


