# GetCustomersMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**customer_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. Customer Ids | [optional] 
**lease_status_type_ids** | **str** | This is an optional field. This field accepts comma seperated multiple values. Lease Status types | [optional] 
**is_agreed_to_terms_only** | **bool** |  | [optional] 
**company_identification_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. company Identification type IDs | [optional] 

## Example

```python
from openapi_client.models.get_customers_method_params import GetCustomersMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersMethodParams from a JSON string
get_customers_method_params_instance = GetCustomersMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetCustomersMethodParams.to_json())

# convert the object into a dict
get_customers_method_params_dict = get_customers_method_params_instance.to_dict()
# create an instance of GetCustomersMethodParams from a dict
get_customers_method_params_from_dict = GetCustomersMethodParams.from_dict(get_customers_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


