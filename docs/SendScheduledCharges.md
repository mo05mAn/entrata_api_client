# SendScheduledCharges


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**SendScheduledChargesMethod**](SendScheduledChargesMethod.md) |  | 

## Example

```python
from entrata_api_client.models.send_scheduled_charges import SendScheduledCharges

# TODO update the JSON string below
json = "{}"
# create an instance of SendScheduledCharges from a JSON string
send_scheduled_charges_instance = SendScheduledCharges.from_json(json)
# print the JSON string representation of the object
print(SendScheduledCharges.to_json())

# convert the object into a dict
send_scheduled_charges_dict = send_scheduled_charges_instance.to_dict()
# create an instance of SendScheduledCharges from a dict
send_scheduled_charges_from_dict = SendScheduledCharges.from_dict(send_scheduled_charges_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


