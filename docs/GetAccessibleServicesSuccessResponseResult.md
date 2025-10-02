# GetAccessibleServicesSuccessResponseResult

The result of the request

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**services** | [**List[GetAccessibleServicesSuccessResponseResultServicesInner]**](GetAccessibleServicesSuccessResponseResultServicesInner.md) | List of services available | 

## Example

```python
from entrata_api_client.models.get_accessible_services_success_response_result import GetAccessibleServicesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessibleServicesSuccessResponseResult from a JSON string
get_accessible_services_success_response_result_instance = GetAccessibleServicesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetAccessibleServicesSuccessResponseResult.to_json())

# convert the object into a dict
get_accessible_services_success_response_result_dict = get_accessible_services_success_response_result_instance.to_dict()
# create an instance of GetAccessibleServicesSuccessResponseResult from a dict
get_accessible_services_success_response_result_from_dict = GetAccessibleServicesSuccessResponseResult.from_dict(get_accessible_services_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


