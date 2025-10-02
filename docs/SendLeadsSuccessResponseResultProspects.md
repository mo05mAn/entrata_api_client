# SendLeadsSuccessResponseResultProspects

Information about the prospects.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prospect** | [**List[SendLeadsSuccessResponseResultProspectsProspectInner]**](SendLeadsSuccessResponseResultProspectsProspectInner.md) | A list of prospect entries. | [optional] 

## Example

```python
from openapi_client.models.send_leads_success_response_result_prospects import SendLeadsSuccessResponseResultProspects

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeadsSuccessResponseResultProspects from a JSON string
send_leads_success_response_result_prospects_instance = SendLeadsSuccessResponseResultProspects.from_json(json)
# print the JSON string representation of the object
print(SendLeadsSuccessResponseResultProspects.to_json())

# convert the object into a dict
send_leads_success_response_result_prospects_dict = send_leads_success_response_result_prospects_instance.to_dict()
# create an instance of SendLeadsSuccessResponseResultProspects from a dict
send_leads_success_response_result_prospects_from_dict = SendLeadsSuccessResponseResultProspects.from_dict(send_leads_success_response_result_prospects_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


