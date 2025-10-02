# GetLeadEvents


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeadEventsMethod**](GetLeadEventsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_lead_events import GetLeadEvents

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEvents from a JSON string
get_lead_events_instance = GetLeadEvents.from_json(json)
# print the JSON string representation of the object
print(GetLeadEvents.to_json())

# convert the object into a dict
get_lead_events_dict = get_lead_events_instance.to_dict()
# create an instance of GetLeadEvents from a dict
get_lead_events_from_dict = GetLeadEvents.from_dict(get_lead_events_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


