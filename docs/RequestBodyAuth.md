# RequestBodyAuth


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 

## Example

```python
from entrata_api_client.models.request_body_auth import RequestBodyAuth

# TODO update the JSON string below
json = "{}"
# create an instance of RequestBodyAuth from a JSON string
request_body_auth_instance = RequestBodyAuth.from_json(json)
# print the JSON string representation of the object
print(RequestBodyAuth.to_json())

# convert the object into a dict
request_body_auth_dict = request_body_auth_instance.to_dict()
# create an instance of RequestBodyAuth from a dict
request_body_auth_from_dict = RequestBodyAuth.from_dict(request_body_auth_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


