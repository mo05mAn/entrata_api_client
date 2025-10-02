# GetTaxFormData


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetTaxFormDataMethod**](GetTaxFormDataMethod.md) |  | 

## Example

```python
from openapi_client.models.get_tax_form_data import GetTaxFormData

# TODO update the JSON string below
json = "{}"
# create an instance of GetTaxFormData from a JSON string
get_tax_form_data_instance = GetTaxFormData.from_json(json)
# print the JSON string representation of the object
print(GetTaxFormData.to_json())

# convert the object into a dict
get_tax_form_data_dict = get_tax_form_data_instance.to_dict()
# create an instance of GetTaxFormData from a dict
get_tax_form_data_from_dict = GetTaxFormData.from_dict(get_tax_form_data_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


