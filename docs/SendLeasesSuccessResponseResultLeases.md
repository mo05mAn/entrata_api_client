# SendLeasesSuccessResponseResultLeases


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**lease** | [**List[SendLeasesSuccessResponseResultLeasesLeaseInner]**](SendLeasesSuccessResponseResultLeasesLeaseInner.md) |  | 

## Example

```python
from openapi_client.models.send_leases_success_response_result_leases import SendLeasesSuccessResponseResultLeases

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeasesSuccessResponseResultLeases from a JSON string
send_leases_success_response_result_leases_instance = SendLeasesSuccessResponseResultLeases.from_json(json)
# print the JSON string representation of the object
print(SendLeasesSuccessResponseResultLeases.to_json())

# convert the object into a dict
send_leases_success_response_result_leases_dict = send_leases_success_response_result_leases_instance.to_dict()
# create an instance of SendLeasesSuccessResponseResultLeases from a dict
send_leases_success_response_result_leases_from_dict = SendLeasesSuccessResponseResultLeases.from_dict(send_leases_success_response_result_leases_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


