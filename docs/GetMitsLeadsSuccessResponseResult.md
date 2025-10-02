# GetMitsLeadsSuccessResponseResult

The result data of the request.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency_code** | **str** | The currency code used in the request. | [optional] 
**lead_management** | [**List[GetMitsLeadsSuccessResponseResultLeadManagementInner]**](GetMitsLeadsSuccessResponseResultLeadManagementInner.md) | A list of lead management entries. | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_leads_success_response_result import GetMitsLeadsSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsLeadsSuccessResponseResult from a JSON string
get_mits_leads_success_response_result_instance = GetMitsLeadsSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(GetMitsLeadsSuccessResponseResult.to_json())

# convert the object into a dict
get_mits_leads_success_response_result_dict = get_mits_leads_success_response_result_instance.to_dict()
# create an instance of GetMitsLeadsSuccessResponseResult from a dict
get_mits_leads_success_response_result_from_dict = GetMitsLeadsSuccessResponseResult.from_dict(get_mits_leads_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


