# UpdateLeadsR1SuccessResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | A unique identifier for the request. | 
**result** | [**UpdateLeadsR1SuccessResponseResult**](UpdateLeadsR1SuccessResponseResult.md) |  | 

## Example

```python
from openapi_client.models.update_leads_r1_success_response import UpdateLeadsR1SuccessResponse

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR1SuccessResponse from a JSON string
update_leads_r1_success_response_instance = UpdateLeadsR1SuccessResponse.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR1SuccessResponse.to_json())

# convert the object into a dict
update_leads_r1_success_response_dict = update_leads_r1_success_response_instance.to_dict()
# create an instance of UpdateLeadsR1SuccessResponse from a dict
update_leads_r1_success_response_from_dict = UpdateLeadsR1SuccessResponse.from_dict(update_leads_r1_success_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


