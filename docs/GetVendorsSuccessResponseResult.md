# GetVendorsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendors** | [**GetVendorsSuccessResponseResultVendors**](GetVendorsSuccessResponseResultVendors.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_vendors_success_response_result import GetVendorsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResult from a JSON string
get_vendors_success_response_result_instance = GetVendorsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResult.to_json())

# convert the object into a dict
get_vendors_success_response_result_dict = get_vendors_success_response_result_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResult from a dict
get_vendors_success_response_result_from_dict = GetVendorsSuccessResponseResult.from_dict(get_vendors_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


