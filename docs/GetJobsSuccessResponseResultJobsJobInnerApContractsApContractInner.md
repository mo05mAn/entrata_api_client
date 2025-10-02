# GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the AP contract. | 
**name** | **str** | The name of the AP contract. | 
**contract_total** | **str** | The total value of the AP contract. | 
**contract_vendor** | **str** | The vendor associated with the AP contract. | 
**planned_start_date** | **date** | The planned start date for the AP contract. | 
**planned_completion_date** | **date** | The planned completion date for the AP contract. | 
**actual_start_date** | **date** | The actual start date of the AP contract. | 
**actual_completion_date** | **date** | The actual completion date of the AP contract. | 
**ap_codes** | [**GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodes**](GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodes.md) |  | 

## Example

```python
from entrata_api_client.models.get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner import GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInner from a JSON string
get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_instance = GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInner.from_json(json)
# print the JSON string representation of the object
print(GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInner.to_json())

# convert the object into a dict
get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_dict = get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_instance.to_dict()
# create an instance of GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInner from a dict
get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_from_dict = GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInner.from_dict(get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


