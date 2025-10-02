# GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**attributes** | [**GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerAttributes**](GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerAttributes.md) |  | 
**total_packages** | **str** | Total number of packages in the batch | 
**total_picked_up** | **str** | Total number of packages picked up | 
**total_delivered** | **str** | Total number of packages delivered | 
**total_print** | **str** | Total number of packages printed | 
**total_resend** | **str** | Total number of packages resent | 
**package_batch_date** | **str** | Date of the package batch | 
**packages** | [**GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackages**](GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInnerPackages.md) |  | 

## Example

```python
from entrata_api_client.models.get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner import GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInner from a JSON string
get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_instance = GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInner.from_json(json)
# print the JSON string representation of the object
print(GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInner.to_json())

# convert the object into a dict
get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_dict = get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_instance.to_dict()
# create an instance of GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInner from a dict
get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_from_dict = GetParcelAlertsSuccessResponseResponseResultPackageBatchesPackageBatchInner.from_dict(get_parcel_alerts_success_response_response_result_package_batches_package_batch_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


