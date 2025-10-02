# SearchCustomersSuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | The unique identifier for the request | 
**result** | [**SearchCustomersSuccessResponseResult**](SearchCustomersSuccessResponseResult.md) |  | 

## Example

```python
from entrata_api_client.models.search_customers_success_response import SearchCustomersSuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of SearchCustomersSuccessResponse from a JSON string
search_customers_success_response_instance = SearchCustomersSuccessResponse.from_json(json)
# print the JSON string representation of the object
print(SearchCustomersSuccessResponse.to_json())

# convert the object into a dict
search_customers_success_response_dict = search_customers_success_response_instance.to_dict()
# create an instance of SearchCustomersSuccessResponse from a dict
search_customers_success_response_from_dict = SearchCustomersSuccessResponse.from_dict(search_customers_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


