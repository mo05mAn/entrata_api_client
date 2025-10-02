# UpdateLeaseSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **str** | Status of the lease update | 
**lease_id** | **str** | Unique identifier for the lease | 
**message** | **str** | Message detailing the result of the lease update | 

## Example

```python
from entrata_api_client.models.update_lease_success_response_result import UpdateLeaseSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateLeaseSuccessResponseResult from a JSON string
update_lease_success_response_result_instance = UpdateLeaseSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(UpdateLeaseSuccessResponseResult.to_json())

# convert the object into a dict
update_lease_success_response_result_dict = update_lease_success_response_result_instance.to_dict()
# create an instance of UpdateLeaseSuccessResponseResult from a dict
update_lease_success_response_result_from_dict = UpdateLeaseSuccessResponseResult.from_dict(update_lease_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


