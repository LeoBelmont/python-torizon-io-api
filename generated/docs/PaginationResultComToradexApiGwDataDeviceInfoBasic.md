# PaginationResultComToradexApiGwDataDeviceInfoBasic


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**values** | [**List[DeviceInfoBasic]**](DeviceInfoBasic.md) |  | [optional] 
**total** | **int** |  | 
**offset** | **int** |  | 
**limit** | **int** |  | 

## Example

```python
from torizon_io_api.models.pagination_result_com_toradex_api_gw_data_device_info_basic import PaginationResultComToradexApiGwDataDeviceInfoBasic

# TODO update the JSON string below
json = "{}"
# create an instance of PaginationResultComToradexApiGwDataDeviceInfoBasic from a JSON string
pagination_result_com_toradex_api_gw_data_device_info_basic_instance = PaginationResultComToradexApiGwDataDeviceInfoBasic.from_json(json)
# print the JSON string representation of the object
print(PaginationResultComToradexApiGwDataDeviceInfoBasic.to_json())

# convert the object into a dict
pagination_result_com_toradex_api_gw_data_device_info_basic_dict = pagination_result_com_toradex_api_gw_data_device_info_basic_instance.to_dict()
# create an instance of PaginationResultComToradexApiGwDataDeviceInfoBasic from a dict
pagination_result_com_toradex_api_gw_data_device_info_basic_from_dict = PaginationResultComToradexApiGwDataDeviceInfoBasic.from_dict(pagination_result_com_toradex_api_gw_data_device_info_basic_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


