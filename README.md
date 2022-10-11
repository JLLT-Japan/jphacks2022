# jphacks2022

### About the data
This is data on Official land prices and Real estate transaction prices provided by the Ministry of Land.

The official land price is the value of land per square meter at a point determined by the Ministry of Land.
Real estate transaction prices are the contract prices of houses and land actually bought and sold.

国土交通省が提供する公示地価と宅地建物取引価格のデータです。

公示地価とは、国土交通省が定める地点における1平方メートルあたりの土地の価格です。

不動産取引価格とは、実際に売買された住宅や土地の成約価格です。

### Field Descriptions

##### Official land prices (地価公示)

| Field Name| Description |
| ---- | ---- |
| longitude | 経度 |
| latitude | 緯度 |
| sequential_number | 連番 |
| district | 市区町村名 |
| address | 所在並びに地番 |
| street_address | 住居表示 |
| lot_size | 地積 |
| indication_use | 利用状況表示 |
| building_structure | 建物構造 |
| shape_category | 形状区分 |
| width_ratio | 間口（比率） |
| depth_ratio | 奥行（比率） |
| floor_above_ground | 階層（地上） |
| floor_underground | 階層（地下） |
| front_road_classification | 前面道路区分 |
| direction_front_road | 前面道路の方位区分 |
| front_road_width | 前面道路の幅員 |
| side_road_classification | 側道区分 |
| directional_classification_side_road | 側道方位区分 |
| proximity_traffic_facilities | 交通施設との近接区分 |
| current_status_land_surrounding_area | 周辺の土地の利用の現況 |
| station_name | 駅名 |
| station_distance | 駅距離 |
| purpose_classification | 用途区分 |
| fire_prevention_category | 防火区分 |
| urban_planning_classification | 都市計画区分 |
| high_altitude_district | 高度地区 |
| forestry_classification | 森林区分 |
| park_classification | 公園区分 |
| building_land_ratio | 建蔽率 |
| floor_area_ratio | 容積率 |
| percentage_change_previous_year | 対前年変動率 |
| selection_year_bit | 選定年次ビット |
| seireki | 該当年 |
| price | 公示価格 |


##### Real estate transaction prices (不動産取引価格)

|Field Name| Description |
| ---- | ---- |
| param_period | 年期 |
| param_prefecture | 都道府県コード |
| typename | 取引の種類 |
| region | 取引の種別カテゴリ |
| municipalitycode | 市区町村コード |
| prefecture | 都道府県 |
| municipality | 市区町村 |
| districtname | 地区 |
| tradeprice | 取引価格（総額） |
| area | 面積（平方メートル） |
| landshape | 土地の形状 |
| frontage | 間口 |
| totalfloorarea | 延床面積(平方メートル) |
| buildingyear | 建築年 |
| structure | 建物の構造 |
| usetype | 用途 |
| purpose | 今後の利用目的 |
| direction | 前面道路：方位 |
| classification | 前面道路：種類 |
| breadth | 前面道路：幅員(m) |
| cityplanning | 都市計画 |
| coverageratio | 建ぺい率(%) |
| floorarearatio | 容積率(%) |
| period | 取引時点 |
| remarks | 取引の事情等 |
