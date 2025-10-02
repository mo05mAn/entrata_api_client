# UpdateScheduledChargesR2


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateScheduledChargesR2Method**](UpdateScheduledChargesR2Method.md) |  | 

## Example

```python
from entrata_api_client.models.update_scheduled_charges_r2 import UpdateScheduledChargesR2

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateScheduledChargesR2 from a JSON string
update_scheduled_charges_r2_instance = UpdateScheduledChargesR2.from_json(json)
# print the JSON string representation of the object
print(UpdateScheduledChargesR2.to_json())

# convert the object into a dict
update_scheduled_charges_r2_dict = update_scheduled_charges_r2_instance.to_dict()
# create an instance of UpdateScheduledChargesR2 from a dict
update_scheduled_charges_r2_from_dict = UpdateScheduledChargesR2.from_dict(update_scheduled_charges_r2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


