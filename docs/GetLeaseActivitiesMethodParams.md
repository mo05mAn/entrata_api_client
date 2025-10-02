# GetLeaseActivitiesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Property Id | 
**lease_id** | **int** | This is a required field. This field accepts single value. | 
**created_on_date_to** | **date** | This is an optional field. This field accepts single value. | [optional] 
**created_on_date_from** | **date** | This is an optional field. This field accepts single value. | [optional] 
**event_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 
**lease_status_type_ids** | **int** | This is an optional field. This field accepts comma seperated multiple values. | [optional] 

## Example

```python
from entrata_api_client.models.get_lease_activities_method_params import GetLeaseActivitiesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetLeaseActivitiesMethodParams from a JSON string
get_lease_activities_method_params_instance = GetLeaseActivitiesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetLeaseActivitiesMethodParams.to_json())

# convert the object into a dict
get_lease_activities_method_params_dict = get_lease_activities_method_params_instance.to_dict()
# create an instance of GetLeaseActivitiesMethodParams from a dict
get_lease_activities_method_params_from_dict = GetLeaseActivitiesMethodParams.from_dict(get_lease_activities_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


