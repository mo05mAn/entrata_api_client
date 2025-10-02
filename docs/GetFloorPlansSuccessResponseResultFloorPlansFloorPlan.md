# GetFloorPlansSuccessResponseResultFloorPlansFloorPlan


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**identification** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanIdentification.md) |  | 
**name** | **str** | Name of the floor plan | 
**property_id** | **int** | Property ID associated with the floor plan | 
**floorplan_groups** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFloorplanGroups**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFloorplanGroups.md) |  | 
**comment** | **str** | Comment related to the floor plan | 
**unit_count** | **str** | Number of units in the floor plan | 
**units_available** | **str** | Number of available units in the floor plan | 
**unit_types** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanUnitTypes**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanUnitTypes.md) |  | 
**is_disabled** | **bool** | Indicates whether the floor plan is disabled | 
**room** | [**List[GetFloorPlansSuccessResponseResultFloorPlansFloorPlanRoomInner]**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanRoomInner.md) | List of rooms in the floor plan | 
**square_feet** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanSquareFeet**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanSquareFeet.md) |  | 
**market_rent** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanMarketRent**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanMarketRent.md) |  | 
**deposit** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit.md) |  | 
**amenity** | [**List[GetFloorPlansSuccessResponseResultFloorPlansFloorPlanAmenityInner]**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanAmenityInner.md) | Amenities available in the floor plan | 
**file** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanFile.md) |  | 

## Example

```python
from entrata_api_client.models.get_floor_plans_success_response_result_floor_plans_floor_plan import GetFloorPlansSuccessResponseResultFloorPlansFloorPlan

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlan from a JSON string
get_floor_plans_success_response_result_floor_plans_floor_plan_instance = GetFloorPlansSuccessResponseResultFloorPlansFloorPlan.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansSuccessResponseResultFloorPlansFloorPlan.to_json())

# convert the object into a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_dict = get_floor_plans_success_response_result_floor_plans_floor_plan_instance.to_dict()
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlan from a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_from_dict = GetFloorPlansSuccessResponseResultFloorPlansFloorPlan.from_dict(get_floor_plans_success_response_result_floor_plans_floor_plan_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


