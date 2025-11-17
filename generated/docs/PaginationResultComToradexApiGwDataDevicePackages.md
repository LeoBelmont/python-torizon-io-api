# PaginationResultComToradexApiGwDataDevicePackages


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**values** | [**List[DevicePackages]**](DevicePackages.md) |  | [optional] 
**total** | **int** |  | 
**offset** | **int** |  | 
**limit** | **int** |  | 

## Example

```python
from torizon_io_api.models.pagination_result_com_toradex_api_gw_data_device_packages import PaginationResultComToradexApiGwDataDevicePackages

# TODO update the JSON string below
json = "{}"
# create an instance of PaginationResultComToradexApiGwDataDevicePackages from a JSON string
pagination_result_com_toradex_api_gw_data_device_packages_instance = PaginationResultComToradexApiGwDataDevicePackages.from_json(json)
# print the JSON string representation of the object
print(PaginationResultComToradexApiGwDataDevicePackages.to_json())

# convert the object into a dict
pagination_result_com_toradex_api_gw_data_device_packages_dict = pagination_result_com_toradex_api_gw_data_device_packages_instance.to_dict()
# create an instance of PaginationResultComToradexApiGwDataDevicePackages from a dict
pagination_result_com_toradex_api_gw_data_device_packages_from_dict = PaginationResultComToradexApiGwDataDevicePackages.from_dict(pagination_result_com_toradex_api_gw_data_device_packages_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


