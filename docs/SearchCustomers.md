# SearchCustomers


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SearchCustomersMethod**](SearchCustomersMethod.md) |  | 

## Example

```python
from entrata_api_client.models.search_customers import SearchCustomers

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCustomers from a JSON string
search_customers_instance = SearchCustomers.from_json(json)
# print the JSON string representation of the object
print(SearchCustomers.to_json())

# convert the object into a dict
search_customers_dict = search_customers_instance.to_dict()
# create an instance of SearchCustomers from a dict
search_customers_from_dict = SearchCustomers.from_dict(search_customers_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


