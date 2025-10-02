# GetLeadEventsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetLeadEventsMethodParams**](GetLeadEventsMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_lead_events_method import GetLeadEventsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeadEventsMethod from a JSON string
get_lead_events_method_instance = GetLeadEventsMethod.from_json(json)
# print the JSON string representation of the object
print(GetLeadEventsMethod.to_json())

# convert the object into a dict
get_lead_events_method_dict = get_lead_events_method_instance.to_dict()
# create an instance of GetLeadEventsMethod from a dict
get_lead_events_method_from_dict = GetLeadEventsMethod.from_dict(get_lead_events_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


