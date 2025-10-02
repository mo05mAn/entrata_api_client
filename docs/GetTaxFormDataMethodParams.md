# GetTaxFormDataMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_ids** | **int** | This is an optional field. This field accepts single value. | [optional] 
**start_date** | **date** | This is a required field. This field accepts single value. | [optional] 
**end_date** | **date** | This is a required field. This field accepts single value. | [optional] 
**generate_for_property_owner** | **int** | This is an optional field. This field accepts single value. If provided as \&quot;0\&quot; then payer will render property info &amp; If provided as \&quot;1\&quot; then Payer node will render the property owners info | [optional] 
**owner_ids** | **str** | This is an optional field. This field accepts single value. | [optional] 
**is_for_indirect_owner** | **int** | This is an optional field. This field accepts single value. If provided false, it will return data only for direct owners. If prov ided true, it will return data for both direct &amp; indirect owners. | [optional] 

## Example

```python
from openapi_client.models.get_tax_form_data_method_params import GetTaxFormDataMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetTaxFormDataMethodParams from a JSON string
get_tax_form_data_method_params_instance = GetTaxFormDataMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetTaxFormDataMethodParams.to_json())

# convert the object into a dict
get_tax_form_data_method_params_dict = get_tax_form_data_method_params_instance.to_dict()
# create an instance of GetTaxFormDataMethodParams from a dict
get_tax_form_data_method_params_from_dict = GetTaxFormDataMethodParams.from_dict(get_tax_form_data_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


