# SendFloorplansSuccessResponseResultFloorplansFloorplanInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**node** | **int** | Node identifier for the floorplan | 
**status** | **str** | Status of the floorplan insertion | 
**floorplan_id** | **int** | Unique identifier for the floorplan | 
**name** | **str** | Name of the floorplan | 
**message** | **str** | Message related to the floorplan insertion | 

## Example

```python
from entrata_api_client.models.send_floorplans_success_response_result_floorplans_floorplan_inner import SendFloorplansSuccessResponseResultFloorplansFloorplanInner

# TODO update the JSON string below
json = "{}"
# create an instance of SendFloorplansSuccessResponseResultFloorplansFloorplanInner from a JSON string
send_floorplans_success_response_result_floorplans_floorplan_inner_instance = SendFloorplansSuccessResponseResultFloorplansFloorplanInner.from_json(json)
# print the JSON string representation of the object
print(SendFloorplansSuccessResponseResultFloorplansFloorplanInner.to_json())

# convert the object into a dict
send_floorplans_success_response_result_floorplans_floorplan_inner_dict = send_floorplans_success_response_result_floorplans_floorplan_inner_instance.to_dict()
# create an instance of SendFloorplansSuccessResponseResultFloorplansFloorplanInner from a dict
send_floorplans_success_response_result_floorplans_floorplan_inner_from_dict = SendFloorplansSuccessResponseResultFloorplansFloorplanInner.from_dict(send_floorplans_success_response_result_floorplans_floorplan_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


