# GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodesApCodeInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The unique identifier for the AP code. | 
**job_phase_id** | **str** | The ID of the associated job phase. | 
**gl_account_id** | **str** | The unique identifier for the general ledger account. | 
**contract_amount** | **str** | The amount specified for the AP code in the contract. | 
**change_order_id** | **str** | The change order ID if applicable. | [optional] 

## Example

```python
from openapi_client.models.get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_ap_codes_ap_code_inner import GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodesApCodeInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodesApCodeInner from a JSON string
get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_ap_codes_ap_code_inner_instance = GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodesApCodeInner.from_json(json)
# print the JSON string representation of the object
print(GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodesApCodeInner.to_json())

# convert the object into a dict
get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_ap_codes_ap_code_inner_dict = get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_ap_codes_ap_code_inner_instance.to_dict()
# create an instance of GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodesApCodeInner from a dict
get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_ap_codes_ap_code_inner_from_dict = GetJobsSuccessResponseResultJobsJobInnerApContractsApContractInnerApCodesApCodeInner.from_dict(get_jobs_success_response_result_jobs_job_inner_ap_contracts_ap_contract_inner_ap_codes_ap_code_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


