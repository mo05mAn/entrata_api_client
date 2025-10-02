# UpdateVendorsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**vendors** | [**UpdateVendorsSuccessResponseResultVendors**](UpdateVendorsSuccessResponseResultVendors.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.update_vendors_success_response_result import UpdateVendorsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateVendorsSuccessResponseResult from a JSON string
update_vendors_success_response_result_instance = UpdateVendorsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateVendorsSuccessResponseResult.to_json())

# convert the object into a dict
update_vendors_success_response_result_dict = update_vendors_success_response_result_instance.to_dict()
# create an instance of UpdateVendorsSuccessResponseResult from a dict
update_vendors_success_response_result_from_dict = UpdateVendorsSuccessResponseResult.from_dict(update_vendors_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


