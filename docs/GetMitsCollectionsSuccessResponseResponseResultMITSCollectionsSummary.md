# GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsSummary


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mits_doc_version** | **str** | Version of the MIT document | 
**generation_time_stamp** | **str** | Timestamp when the document was generated | 
**source_organization** | **str** | Name of the source organization | 
**total_properties** | **str** | Total number of properties | 
**total_lease_files** | **int** | Total number of lease files | 
**total_tenants** | **int** | Total number of tenants | 
**total_open_amount** | **str** | Total open amount | 

## Example

```python
from openapi_client.models.get_mits_collections_success_response_response_result_mits_collections_summary import GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsSummary

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsSummary from a JSON string
get_mits_collections_success_response_response_result_mits_collections_summary_instance = GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsSummary.from_json(json)
# print the JSON string representation of the object
print(GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsSummary.to_json())

# convert the object into a dict
get_mits_collections_success_response_response_result_mits_collections_summary_dict = get_mits_collections_success_response_response_result_mits_collections_summary_instance.to_dict()
# create an instance of GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsSummary from a dict
get_mits_collections_success_response_response_result_mits_collections_summary_from_dict = GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsSummary.from_dict(get_mits_collections_success_response_response_result_mits_collections_summary_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


