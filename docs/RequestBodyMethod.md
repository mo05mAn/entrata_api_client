# RequestBodyMethod


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** |  | 
**version** | **str** |  | [optional] 
**params** | **object** | the service request parameters if any. Replace dummy values from examples with actual values. | [optional] 

## Example

```python
from openapi_client.models.request_body_method import RequestBodyMethod

# TODO update the JSON string below
json = "{}"
# create an instance of RequestBodyMethod from a JSON string
request_body_method_instance = RequestBodyMethod.from_json(json)
# print the JSON string representation of the object
print(RequestBodyMethod.to_json())

# convert the object into a dict
request_body_method_dict = request_body_method_instance.to_dict()
# create an instance of RequestBodyMethod from a dict
request_body_method_from_dict = RequestBodyMethod.from_dict(request_body_method_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


