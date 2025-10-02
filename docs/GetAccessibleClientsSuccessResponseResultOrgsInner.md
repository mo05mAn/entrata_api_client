# GetAccessibleClientsSuccessResponseResultOrgsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subdomain** | **str** | The subdomain of the organization | 
**id** | **int** | The unique identifier of the organization | 
**name** | **str** | The name of the organization | 

## Example

```python
from entrata_api_client.models.get_accessible_clients_success_response_result_orgs_inner import GetAccessibleClientsSuccessResponseResultOrgsInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetAccessibleClientsSuccessResponseResultOrgsInner from a JSON string
get_accessible_clients_success_response_result_orgs_inner_instance = GetAccessibleClientsSuccessResponseResultOrgsInner.from_json(json)
# print the JSON string representation of the object
print(GetAccessibleClientsSuccessResponseResultOrgsInner.to_json())

# convert the object into a dict
get_accessible_clients_success_response_result_orgs_inner_dict = get_accessible_clients_success_response_result_orgs_inner_instance.to_dict()
# create an instance of GetAccessibleClientsSuccessResponseResultOrgsInner from a dict
get_accessible_clients_success_response_result_orgs_inner_from_dict = GetAccessibleClientsSuccessResponseResultOrgsInner.from_dict(get_accessible_clients_success_response_result_orgs_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


