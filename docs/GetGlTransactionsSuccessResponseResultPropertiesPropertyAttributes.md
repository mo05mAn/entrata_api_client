# GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the property. | 
**name** | **str** | The name of the property. | 
**lookup_code** | **str** | The lookup code for the property. | 
**business_unit_code** | **str** | The business unit code for the property. | 

## Example

```python
from entrata_api_client.models.get_gl_transactions_success_response_result_properties_property_attributes import GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes

# TODO update the JSON string below
json = "{}"
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes from a JSON string
get_gl_transactions_success_response_result_properties_property_attributes_instance = GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes.from_json(json)
# print the JSON string representation of the object
print(GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes.to_json())

# convert the object into a dict
get_gl_transactions_success_response_result_properties_property_attributes_dict = get_gl_transactions_success_response_result_properties_property_attributes_instance.to_dict()
# create an instance of GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes from a dict
get_gl_transactions_success_response_result_properties_property_attributes_from_dict = GetGlTransactionsSuccessResponseResultPropertiesPropertyAttributes.from_dict(get_gl_transactions_success_response_result_properties_property_attributes_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


