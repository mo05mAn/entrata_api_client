# GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileProperty


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFilePropertyIdentification**](GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFilePropertyIdentification.md) |  | 
**marketing_name** | **str** | The marketing name of the property | 
**address** | [**List[GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFilePropertyAddressInner]**](GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFilePropertyAddressInner.md) | List of addresses | 
**phone** | [**List[GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFilePropertyPhoneInner]**](GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFilePropertyPhoneInner.md) | List of phone numbers | 

## Example

```python
from entrata_api_client.models.get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_property import GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileProperty

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileProperty from a JSON string
get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_property_instance = GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileProperty.from_json(json)
# print the JSON string representation of the object
print(GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileProperty.to_json())

# convert the object into a dict
get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_property_dict = get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_property_instance.to_dict()
# create an instance of GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileProperty from a dict
get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_property_from_dict = GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileProperty.from_dict(get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_property_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


