# GetAccessibleClientsSuccessResponseResult

The result of the request

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**orgs** | [**List[GetAccessibleClientsSuccessResponseResultOrgsInner]**](GetAccessibleClientsSuccessResponseResultOrgsInner.md) | List of organizations | 

## Example

```python
from openapi_client.models.get_accessible_clients_success_response_result import GetAccessibleClientsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessibleClientsSuccessResponseResult from a JSON string
get_accessible_clients_success_response_result_instance = GetAccessibleClientsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetAccessibleClientsSuccessResponseResult.to_json())

# convert the object into a dict
get_accessible_clients_success_response_result_dict = get_accessible_clients_success_response_result_instance.to_dict()
# create an instance of GetAccessibleClientsSuccessResponseResult from a dict
get_accessible_clients_success_response_result_from_dict = GetAccessibleClientsSuccessResponseResult.from_dict(get_accessible_clients_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


