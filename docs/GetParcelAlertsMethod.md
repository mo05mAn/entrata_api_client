# GetParcelAlertsMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**GetParcelAlertsMethodParams**](GetParcelAlertsMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.get_parcel_alerts_method import GetParcelAlertsMethod

# TODO update the JSON string below
json = "{}"
# create an instance of GetParcelAlertsMethod from a JSON string
get_parcel_alerts_method_instance = GetParcelAlertsMethod.from_json(json)
# print the JSON string representation of the object
print(GetParcelAlertsMethod.to_json())

# convert the object into a dict
get_parcel_alerts_method_dict = get_parcel_alerts_method_instance.to_dict()
# create an instance of GetParcelAlertsMethod from a dict
get_parcel_alerts_method_from_dict = GetParcelAlertsMethod.from_dict(get_parcel_alerts_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


