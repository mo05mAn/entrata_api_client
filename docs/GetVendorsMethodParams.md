# GetVendorsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendor_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. Once passing this parameter web service will return Vendor details for those Vendor Ids. Conditional mandatory, If vendorIds are provided t hen vendorsCodes is not required. | [optional] 
**vendor_codes** | **str** | This is an optional field. This field accepts comma seperated multiple values. Conditional mandatory, If \&quot;vendorsCodes\&quot; are provided then \&quot;vendorIds \&quot; are not required. | [optional] 

## Example

```python
from entrata_api_client.models.get_vendors_method_params import GetVendorsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetVendorsMethodParams from a JSON string
get_vendors_method_params_instance = GetVendorsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetVendorsMethodParams.to_json())

# convert the object into a dict
get_vendors_method_params_dict = get_vendors_method_params_instance.to_dict()
# create an instance of GetVendorsMethodParams from a dict
get_vendors_method_params_from_dict = GetVendorsMethodParams.from_dict(get_vendors_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


