# UpdateLeadsR1SuccessResponseResultProspects

Information about the prospects.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**prospect** | [**List[UpdateLeadsR1SuccessResponseResultProspectsProspectInner]**](UpdateLeadsR1SuccessResponseResultProspectsProspectInner.md) | A list of prospect entries. | [optional] 

## Example

```python
from entrata_api_client.models.update_leads_r1_success_response_result_prospects import UpdateLeadsR1SuccessResponseResultProspects

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR1SuccessResponseResultProspects from a JSON string
update_leads_r1_success_response_result_prospects_instance = UpdateLeadsR1SuccessResponseResultProspects.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR1SuccessResponseResultProspects.to_json())

# convert the object into a dict
update_leads_r1_success_response_result_prospects_dict = update_leads_r1_success_response_result_prospects_instance.to_dict()
# create an instance of UpdateLeadsR1SuccessResponseResultProspects from a dict
update_leads_r1_success_response_result_prospects_from_dict = UpdateLeadsR1SuccessResponseResultProspects.from_dict(update_leads_r1_success_response_result_prospects_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


