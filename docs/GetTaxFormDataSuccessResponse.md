# GetTaxFormDataSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Unique identifier for the request. | 
**code** | **str** | Success response code. | 
**result** | [**GetTaxFormDataSuccessResponseResult**](GetTaxFormDataSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.get_tax_form_data_success_response import GetTaxFormDataSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of GetTaxFormDataSuccessResponse from a JSON string
get_tax_form_data_success_response_instance = GetTaxFormDataSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(GetTaxFormDataSuccessResponse.to_json())

# convert the object into a dict
get_tax_form_data_success_response_dict = get_tax_form_data_success_response_instance.to_dict()
# create an instance of GetTaxFormDataSuccessResponse from a dict
get_tax_form_data_success_response_from_dict = GetTaxFormDataSuccessResponse.from_dict(get_tax_form_data_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


