# GetVendorsSuccessResponseResultVendors


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor** | [**List[GetVendorsSuccessResponseResultVendorsVendorInner]**](GetVendorsSuccessResponseResultVendorsVendorInner.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_vendors_success_response_result_vendors import GetVendorsSuccessResponseResultVendors

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsSuccessResponseResultVendors from a JSON string
get_vendors_success_response_result_vendors_instance = GetVendorsSuccessResponseResultVendors.from_json(json)
# print the JSON string representation of the object
print(GetVendorsSuccessResponseResultVendors.to_json())

# convert the object into a dict
get_vendors_success_response_result_vendors_dict = get_vendors_success_response_result_vendors_instance.to_dict()
# create an instance of GetVendorsSuccessResponseResultVendors from a dict
get_vendors_success_response_result_vendors_from_dict = GetVendorsSuccessResponseResultVendors.from_dict(get_vendors_success_response_result_vendors_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


