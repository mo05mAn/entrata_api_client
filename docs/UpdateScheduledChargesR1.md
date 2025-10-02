# UpdateScheduledChargesR1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**UpdateScheduledChargesR1Method**](UpdateScheduledChargesR1Method.md) |  | 

## Example

```python
from openapi_client.models.update_scheduled_charges_r1 import UpdateScheduledChargesR1

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateScheduledChargesR1 from a JSON string
update_scheduled_charges_r1_instance = UpdateScheduledChargesR1.from_json(json)
# print the JSON string representation of the object
print(UpdateScheduledChargesR1.to_json())

# convert the object into a dict
update_scheduled_charges_r1_dict = update_scheduled_charges_r1_instance.to_dict()
# create an instance of UpdateScheduledChargesR1 from a dict
update_scheduled_charges_r1_from_dict = UpdateScheduledChargesR1.from_dict(update_scheduled_charges_r1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


