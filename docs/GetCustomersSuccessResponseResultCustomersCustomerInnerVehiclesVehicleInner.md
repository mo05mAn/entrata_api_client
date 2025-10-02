# GetCustomersSuccessResponseResultCustomersCustomerInnerVehiclesVehicleInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**model** | **str** | The model of the vehicle | 
**color** | **str** | The color of the vehicle | 
**make** | **str** | The make of the vehicle | 
**license_plate_number** | **str** | The license plate number of the vehicle | 
**state_code** | **str** | State code where the vehicle is registered | 
**year** | **str** | The manufacturing year of the vehicle | 

## Example

```python
from entrata_api_client.models.get_customers_success_response_result_customers_customer_inner_vehicles_vehicle_inner import GetCustomersSuccessResponseResultCustomersCustomerInnerVehiclesVehicleInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCustomersSuccessResponseResultCustomersCustomerInnerVehiclesVehicleInner from a JSON string
get_customers_success_response_result_customers_customer_inner_vehicles_vehicle_inner_instance = GetCustomersSuccessResponseResultCustomersCustomerInnerVehiclesVehicleInner.from_json(json)
# print the JSON string representation of the object
print(GetCustomersSuccessResponseResultCustomersCustomerInnerVehiclesVehicleInner.to_json())

# convert the object into a dict
get_customers_success_response_result_customers_customer_inner_vehicles_vehicle_inner_dict = get_customers_success_response_result_customers_customer_inner_vehicles_vehicle_inner_instance.to_dict()
# create an instance of GetCustomersSuccessResponseResultCustomersCustomerInnerVehiclesVehicleInner from a dict
get_customers_success_response_result_customers_customer_inner_vehicles_vehicle_inner_from_dict = GetCustomersSuccessResponseResultCustomersCustomerInnerVehiclesVehicleInner.from_dict(get_customers_success_response_result_customers_customer_inner_vehicles_vehicle_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


