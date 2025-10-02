# RequestBody


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**RequestBodyMethod**](RequestBodyMethod.md) |  | 

## Example

```python
from entrata_api_client.models.request_body import RequestBody

# TODO update the JSON string below
json = "{}"
# create an instance of RequestBody from a JSON string
request_body_instance = RequestBody.from_json(json)
# print the JSON string representation of the object
print(RequestBody.to_json())

# convert the object into a dict
request_body_dict = request_body_instance.to_dict()
# create an instance of RequestBody from a dict
request_body_from_dict = RequestBody.from_dict(request_body_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


