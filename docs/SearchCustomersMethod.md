# SearchCustomersMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SearchCustomersMethodParams**](SearchCustomersMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.search_customers_method import SearchCustomersMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCustomersMethod from a JSON string
search_customers_method_instance = SearchCustomersMethod.from_json(json)
# print the JSON string representation of the object
print(SearchCustomersMethod.to_json())

# convert the object into a dict
search_customers_method_dict = search_customers_method_instance.to_dict()
# create an instance of SearchCustomersMethod from a dict
search_customers_method_from_dict = SearchCustomersMethod.from_dict(search_customers_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


