# GetParcelAlerts


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetParcelAlertsMethod**](GetParcelAlertsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.get_parcel_alerts import GetParcelAlerts

# TODO update the JSON string below
json = "{}"
# create an instance of GetParcelAlerts from a JSON string
get_parcel_alerts_instance = GetParcelAlerts.from_json(json)
# print the JSON string representation of the object
print(GetParcelAlerts.to_json())

# convert the object into a dict
get_parcel_alerts_dict = get_parcel_alerts_instance.to_dict()
# create an instance of GetParcelAlerts from a dict
get_parcel_alerts_from_dict = GetParcelAlerts.from_dict(get_parcel_alerts_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


