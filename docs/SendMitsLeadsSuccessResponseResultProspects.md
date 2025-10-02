# SendMitsLeadsSuccessResponseResultProspects

Information about the prospects.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prospect** | [**List[SendMitsLeadsSuccessResponseResultProspectsProspectInner]**](SendMitsLeadsSuccessResponseResultProspectsProspectInner.md) | A list of prospect entries. | [optional] 

## Example

```python
from entrata_api_client.models.send_mits_leads_success_response_result_prospects import SendMitsLeadsSuccessResponseResultProspects

# TODO update the JSON string below
json = "{}"
# create an instance of SendMitsLeadsSuccessResponseResultProspects from a JSON string
send_mits_leads_success_response_result_prospects_instance = SendMitsLeadsSuccessResponseResultProspects.from_json(json)
# print the JSON string representation of the object
print(SendMitsLeadsSuccessResponseResultProspects.to_json())

# convert the object into a dict
send_mits_leads_success_response_result_prospects_dict = send_mits_leads_success_response_result_prospects_instance.to_dict()
# create an instance of SendMitsLeadsSuccessResponseResultProspects from a dict
send_mits_leads_success_response_result_prospects_from_dict = SendMitsLeadsSuccessResponseResultProspects.from_dict(send_mits_leads_success_response_result_prospects_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


