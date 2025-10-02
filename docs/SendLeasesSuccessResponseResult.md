# SendLeasesSuccessResponseResult


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**leases** | [**SendLeasesSuccessResponseResultLeases**](SendLeasesSuccessResponseResultLeases.md) |  | 

## Example

```python
from entrata_api_client.models.send_leases_success_response_result import SendLeasesSuccessResponseResult

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeasesSuccessResponseResult from a JSON string
send_leases_success_response_result_instance = SendLeasesSuccessResponseResult.from_json(json)
# print the JSON string representation of the object
print(SendLeasesSuccessResponseResult.to_json())

# convert the object into a dict
send_leases_success_response_result_dict = send_leases_success_response_result_instance.to_dict()
# create an instance of SendLeasesSuccessResponseResult from a dict
send_leases_success_response_result_from_dict = SendLeasesSuccessResponseResult.from_dict(send_leases_success_response_result_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


