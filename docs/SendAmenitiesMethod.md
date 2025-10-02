# SendAmenitiesMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | [**SendAmenitiesMethodParams**](SendAmenitiesMethodParams.md) |  | [optional] 

## Example

```python
from openapi_client.models.send_amenities_method import SendAmenitiesMethod

# TODO update the JSON string below
json = "{}"
# create an instance of SendAmenitiesMethod from a JSON string
send_amenities_method_instance = SendAmenitiesMethod.from_json(json)
# print the JSON string representation of the object
print(SendAmenitiesMethod.to_json())

# convert the object into a dict
send_amenities_method_dict = send_amenities_method_instance.to_dict()
# create an instance of SendAmenitiesMethod from a dict
send_amenities_method_from_dict = SendAmenitiesMethod.from_dict(send_amenities_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


