# GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInnerAttributes**](GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInnerAttributes.md) |  | 
**lease_id** | **int** | Lease ID associated with the package | 
**customer_id** | **int** | Customer ID associated with the package | 
**customer_email_address** | **str** | Customer email address | 
**customer_name** | **str** | Customer name | 
**package_type** | **str** | Type of the package | 
**package_status** | **str** | Status of the package | 
**tracking_number** | **str** | Tracking number for the package | 
**shipping_vendor** | **str** | Shipping vendor for the package | 
**emailed_on** | **str** | Date when the package email was sent | 
**package_date** | **str** | Date of the package | 
**unit_space_id** | **int** | ID of the unit space | [optional] 
**unit_number** | **str** | Unit number associated with the package | [optional] 
**printed_on** | **str** | Date when the package was printed | [optional] 

## Example

```python
from openapi_client.models.get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_packages_package_inner import GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInner from a JSON string
get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_packages_package_inner_instance = GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInner.from_json(json)
# print the JSON string representation of the object
print(GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInner.to_json())

# convert the object into a dict
get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_packages_package_inner_dict = get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_packages_package_inner_instance.to_dict()
# create an instance of GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInner from a dict
get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_packages_package_inner_from_dict = GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackagesPackageInner.from_dict(get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_packages_package_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


