# OrgsV1LeasingcenterPostRequestInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**auth** | [**RequestBodyAuth**](RequestBodyAuth.md) |  | 
**request_id** | **str** | an arbitary value to relate with response. | [optional] 
**method** | [**GetLeasingCenterPickListsMethod**](GetLeasingCenterPickListsMethod.md) |  | 

## Example

```python
from entrata_api_client.models.orgs_v1_leasingcenter_post_request_inner import OrgsV1LeasingcenterPostRequestInner

# TODO update the JSON string below
json = "{}"
# create an instance of OrgsV1LeasingcenterPostRequestInner from a JSON string
orgs_v1_leasingcenter_post_request_inner_instance = OrgsV1LeasingcenterPostRequestInner.from_json(json)
# print the JSON string representation of the object
print(OrgsV1LeasingcenterPostRequestInner.to_json())

# convert the object into a dict
orgs_v1_leasingcenter_post_request_inner_dict = orgs_v1_leasingcenter_post_request_inner_instance.to_dict()
# create an instance of OrgsV1LeasingcenterPostRequestInner from a dict
orgs_v1_leasingcenter_post_request_inner_from_dict = OrgsV1LeasingcenterPostRequestInner.from_dict(orgs_v1_leasingcenter_post_request_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


