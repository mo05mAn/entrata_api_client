# GetParcelAlertsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**lease_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**customer_id** | **int** | This is a required field. This field accepts single value. | [optional] 
**is_active** | **int** | This is an optional field. This field accepts single value. | [optional] 

## Example

```python
from openapi_client.models.get_parcel_alerts_method_params import GetParcelAlertsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetParcelAlertsMethodParams from a JSON string
get_parcel_alerts_method_params_instance = GetParcelAlertsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetParcelAlertsMethodParams.to_json())

# convert the object into a dict
get_parcel_alerts_method_params_dict = get_parcel_alerts_method_params_instance.to_dict()
# create an instance of GetParcelAlertsMethodParams from a dict
get_parcel_alerts_method_params_from_dict = GetParcelAlertsMethodParams.from_dict(get_parcel_alerts_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


