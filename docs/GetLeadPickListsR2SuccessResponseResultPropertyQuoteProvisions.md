# GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions

Quote provisions associated with the property.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**quote_provision** | [**List[GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisionsQuoteProvisionInner]**](GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisionsQuoteProvisionInner.md) | A list of quote provisions. | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_pick_lists_r2_success_response_result_property_quote_provisions import GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions from a JSON string
get_lead_pick_lists_r2_success_response_result_property_quote_provisions_instance = GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions.from_json(json)
# print the JSON string representation of the object
print(GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions.to_json())

# convert the object into a dict
get_lead_pick_lists_r2_success_response_result_property_quote_provisions_dict = get_lead_pick_lists_r2_success_response_result_property_quote_provisions_instance.to_dict()
# create an instance of GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions from a dict
get_lead_pick_lists_r2_success_response_result_property_quote_provisions_from_dict = GetLeadPickListsR2SuccessResponseResultPropertyQuoteProvisions.from_dict(get_lead_pick_lists_r2_success_response_result_property_quote_provisions_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


