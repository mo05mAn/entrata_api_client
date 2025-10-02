# GetEvictedLeasesMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. Provide a valid propertyId. | 
**eviction_start_date_from** | **date** | This is an optional field. This field accepts single value. Provide a valid evictionStartDateFrom. | [optional] 
**eviction_start_date_to** | **date** | This is an optional field. This field accepts single value. Provide a valid evictionStartDateTo | [optional] 

## Example

```python
from entrata_api_client.models.get_evicted_leases_method_params import GetEvictedLeasesMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesMethodParams from a JSON string
get_evicted_leases_method_params_instance = GetEvictedLeasesMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesMethodParams.to_json())

# convert the object into a dict
get_evicted_leases_method_params_dict = get_evicted_leases_method_params_instance.to_dict()
# create an instance of GetEvictedLeasesMethodParams from a dict
get_evicted_leases_method_params_from_dict = GetEvictedLeasesMethodParams.from_dict(get_evicted_leases_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


