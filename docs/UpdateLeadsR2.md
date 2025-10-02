# UpdateLeadsR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateLeadsR2Method**](UpdateLeadsR2Method.md) |  | 

## Example

```python
from entrata_api_client.models.update_leads_r2 import UpdateLeadsR2

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeadsR2 from a JSON string
update_leads_r2_instance = UpdateLeadsR2.from_json(json)
# print the JSON string representation of the object
print(UpdateLeadsR2.to_json())

# convert the object into a dict
update_leads_r2_dict = update_leads_r2_instance.to_dict()
# create an instance of UpdateLeadsR2 from a dict
update_leads_r2_from_dict = UpdateLeadsR2.from_dict(update_leads_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


