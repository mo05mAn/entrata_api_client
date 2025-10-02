# UpdateLeadsR2SuccessResponseResultProspectsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **str** | A node identifier for the prospect. | [optional] 
**status** | **str** | The status of the prospect. | [optional] 
**message** | **str** | A message associated with the prospect. | [optional] 

## Example

```python
from openapi_client.models.update_leads_r2_success_response_result_prospects_inner import UpdateLeadsR2SuccessResponseResultProspectsInner

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR2SuccessResponseResultProspectsInner from a JSON string
update_leads_r2_success_response_result_prospects_inner_instance = UpdateLeadsR2SuccessResponseResultProspectsInner.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR2SuccessResponseResultProspectsInner.to_json())

# convert the object into a dict
update_leads_r2_success_response_result_prospects_inner_dict = update_leads_r2_success_response_result_prospects_inner_instance.to_dict()
# create an instance of UpdateLeadsR2SuccessResponseResultProspectsInner from a dict
update_leads_r2_success_response_result_prospects_inner_from_dict = UpdateLeadsR2SuccessResponseResultProspectsInner.from_dict(update_leads_r2_success_response_result_prospects_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


