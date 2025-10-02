# GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier for the property. | 
**name** | **str** | Name of the property. | 
**address** | [**List[GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFilePropertyAddressInner]**](GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFilePropertyAddressInner.md) |  | 
**phone** | [**List[GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFilePropertyPhoneInner]**](GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFilePropertyPhoneInner.md) |  | 

## Example

```python
from openapi_client.models.get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_property import GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileProperty from a JSON string
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_property_instance = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileProperty.from_json(json)
# print the JSON string representation of the object
print(GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileProperty.to_json())

# convert the object into a dict
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_property_dict = get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_property_instance.to_dict()
# create an instance of GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileProperty from a dict
get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_property_from_dict = GetEvictedLeasesSuccessResponseResponseResultEvictedLeasesPropertyFilesPropertyFileProperty.from_dict(get_evicted_leases_success_response_response_result_evicted_leases_property_files_property_file_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


