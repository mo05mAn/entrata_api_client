# UpdateLeadsR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateLeadsR1Method**](UpdateLeadsR1Method.md) |  | 

## Example

```python
from openapi_client.models.update_leads_r1 import UpdateLeadsR1

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR1 from a JSON string
update_leads_r1_instance = UpdateLeadsR1.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR1.to_json())

# convert the object into a dict
update_leads_r1_dict = update_leads_r1_instance.to_dict()
# create an instance of UpdateLeadsR1 from a dict
update_leads_r1_from_dict = UpdateLeadsR1.from_dict(update_leads_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


