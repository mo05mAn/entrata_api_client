# GetMitsCollectionsMethodParams


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**property_id** | **int** | This is a required field. This field accepts single value. | 
**include_evictions** | **int** | This is an optional field. This field accepts single value. Include Evictions leases | [optional] 
**from_date** | **date** | This is an optional field. This field accepts single value. From Date | [optional] 
**transaction_from_date** | **date** | This is an optional field. This field accepts single value. transactionFromDate | [optional] 

## Example

```python
from entrata_api_client.models.get_mits_collections_method_params import GetMitsCollectionsMethodParams

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsCollectionsMethodParams from a JSON string
get_mits_collections_method_params_instance = GetMitsCollectionsMethodParams.from_json(json)
# print the JSON string representation of the object
print(GetMitsCollectionsMethodParams.to_json())

# convert the object into a dict
get_mits_collections_method_params_dict = get_mits_collections_method_params_instance.to_dict()
# create an instance of GetMitsCollectionsMethodParams from a dict
get_mits_collections_method_params_from_dict = GetMitsCollectionsMethodParams.from_dict(get_mits_collections_method_params_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


