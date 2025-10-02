# GetTaxFormDataMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetTaxFormDataMethodParams**](GetTaxFormDataMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_tax_form_data_method import GetTaxFormDataMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetTaxFormDataMethod from a JSON string
get_tax_form_data_method_instance = GetTaxFormDataMethod.from_json(json)
# print the JSON string representation of the object
print(GetTaxFormDataMethod.to_json())

# convert the object into a dict
get_tax_form_data_method_dict = get_tax_form_data_method_instance.to_dict()
# create an instance of GetTaxFormDataMethod from a dict
get_tax_form_data_method_from_dict = GetTaxFormDataMethod.from_dict(get_tax_form_data_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


