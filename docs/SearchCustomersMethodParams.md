# SearchCustomersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id. This is system ID associated with each property. | 
**search** | **str** | This is a required field. This field accepts single value. Search string accepts phone number, name, building, unit, secondary number. | 

## Example

```python
from openapi_client.models.search_customers_method_params import SearchCustomersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCustomersMethodParams from a JSON string
search_customers_method_params_instance = SearchCustomersMethodParams.from_json(json)
# print the JSON string representation of the object
print(SearchCustomersMethodParams.to_json())

# convert the object into a dict
search_customers_method_params_dict = search_customers_method_params_instance.to_dict()
# create an instance of SearchCustomersMethodParams from a dict
search_customers_method_params_from_dict = SearchCustomersMethodParams.from_dict(search_customers_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


