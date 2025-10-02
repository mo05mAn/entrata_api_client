# GetLeadsSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **str** | The property identifier. | 
**currency_code** | **str** | The currency code used. | 
**prospects** | [**GetLeadsSuccessResponseResultProspects**](GetLeadsSuccessResponseResultProspects.md) |  | 

## Example

```python
from openapi_client.models.get_leads_success_response_result import GetLeadsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadsSuccessResponseResult from a JSON string
get_leads_success_response_result_instance = GetLeadsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetLeadsSuccessResponseResult.to_json())

# convert the object into a dict
get_leads_success_response_result_dict = get_leads_success_response_result_instance.to_dict()
# create an instance of GetLeadsSuccessResponseResult from a dict
get_leads_success_response_result_from_dict = GetLeadsSuccessResponseResult.from_dict(get_leads_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


