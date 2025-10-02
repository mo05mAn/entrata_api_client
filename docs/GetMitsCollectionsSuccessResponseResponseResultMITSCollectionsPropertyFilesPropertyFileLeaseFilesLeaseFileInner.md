# GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerIdentification**](GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerIdentification.md) |  | 
**collection_status** | **str** | The collection status | 
**move_in_date** | **str** | Move-in date | 
**move_out_date** | **str** | Move-out date | 
**notice_to_vacate_date** | **str** | Notice to vacate date | 
**lease_begin** | **str** | Lease begin date | 
**lease_end** | **str** | Lease end date | 
**fmo_processed_on** | **str** | Date the FMO was processed | 
**rent_due_from_date** | **str** | Rent due from date | 
**rent_due_to_date** | **str** | Rent due to date | 
**last_payment_date** | **str** | Last payment date | 
**total_lease_open_amount** | **str** | Total open amount for the lease | 
**building_name** | **str** | Name of the building | 
**unit** | [**GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerUnit**](GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerUnit.md) |  | 
**tenants** | [**List[GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsInner]**](GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerTenantsInner.md) |  | 
**file_transactions** | [**List[GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerFileTransactionsInner]**](GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInnerFileTransactionsInner.md) |  | 

## Example

```python
from openapi_client.models.get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_lease_files_lease_file_inner import GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInner from a JSON string
get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_lease_files_lease_file_inner_instance = GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInner.from_json(json)
# print the JSON string representation of the object
print(GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInner.to_json())

# convert the object into a dict
get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_lease_files_lease_file_inner_dict = get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_lease_files_lease_file_inner_instance.to_dict()
# create an instance of GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInner from a dict
get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_lease_files_lease_file_inner_from_dict = GetMitsCollectionsSuccessResponseResponseResultMITSCollectionsPropertyFilesPropertyFileLeaseFilesLeaseFileInner.from_dict(get_mits_collections_success_response_response_result_mits_collections_property_files_property_file_lease_files_lease_file_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


