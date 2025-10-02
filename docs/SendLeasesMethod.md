# SendLeasesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendLeasesMethodParams**](SendLeasesMethodParams.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.send_leases_method import SendLeasesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendLeasesMethod from a JSON string
send_leases_method_instance = SendLeasesMethod.from_json(json)
# print the JSON string representation of the object
print(SendLeasesMethod.to_json())

# convert the object into a dict
send_leases_method_dict = send_leases_method_instance.to_dict()
# create an instance of SendLeasesMethod from a dict
send_leases_method_from_dict = SendLeasesMethod.from_dict(send_leases_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


