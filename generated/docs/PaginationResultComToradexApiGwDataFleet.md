# PaginationResultComToradexApiGwDataFleet


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**values** | [**List[Fleet]**](Fleet.md) |  | [optional] 
**total** | **int** |  | 
**offset** | **int** |  | 
**limit** | **int** |  | 

## Example

```python
from torizon_io_api.models.pagination_result_com_toradex_api_gw_data_fleet import PaginationResultComToradexApiGwDataFleet

# TODO update the JSON string below
json = "{}"
# create an instance of PaginationResultComToradexApiGwDataFleet from a JSON string
pagination_result_com_toradex_api_gw_data_fleet_instance = PaginationResultComToradexApiGwDataFleet.from_json(json)
# print the JSON string representation of the object
print(PaginationResultComToradexApiGwDataFleet.to_json())

# convert the object into a dict
pagination_result_com_toradex_api_gw_data_fleet_dict = pagination_result_com_toradex_api_gw_data_fleet_instance.to_dict()
# create an instance of PaginationResultComToradexApiGwDataFleet from a dict
pagination_result_com_toradex_api_gw_data_fleet_from_dict = PaginationResultComToradexApiGwDataFleet.from_dict(pagination_result_com_toradex_api_gw_data_fleet_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


