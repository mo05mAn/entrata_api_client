# GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit

Deposit details for the floor plan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDepositAmount**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDepositAmount.md) |  | [optional] 
**attributes** | [**GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDepositAttributes**](GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDepositAttributes.md) |  | [optional] 

## Example

```python
from entrata_api_client.models.get_floor_plans_success_response_result_floor_plans_floor_plan_deposit import GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit

# TODO update the JSON string below
json = "{}"
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit from a JSON string
get_floor_plans_success_response_result_floor_plans_floor_plan_deposit_instance = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit.from_json(json)
# print the JSON string representation of the object
print(GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit.to_json())

# convert the object into a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_deposit_dict = get_floor_plans_success_response_result_floor_plans_floor_plan_deposit_instance.to_dict()
# create an instance of GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit from a dict
get_floor_plans_success_response_result_floor_plans_floor_plan_deposit_from_dict = GetFloorPlansSuccessResponseResultFloorPlansFloorPlanDeposit.from_dict(get_floor_plans_success_response_result_floor_plans_floor_plan_deposit_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


