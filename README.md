# jphacks2022

### About the data
This is data on Official land prices and Real estate transaction prices provided by the Ministry of Land.

The official land price is the value of land per square meter at a point determined by the Ministry of Land.
Real estate transaction prices are the contract prices of houses and land actually bought and sold.


### Field Descriptions

##### Official land prices (地価公示)

| Field Name| Description |
| ---- | ---- |
| longitude | 経度 |
| latitude | 緯度 |
| location_code | 所在地コード |
| purpose | 用途 |
| sequential_number | 連番 |
| years | 年次 |
| previous_year_location_code | 前年所在地コード |
| use_previous_years | 前年用途 |
| sequential_number_previous_year | 前年連番 |
| district | 市区町村名 |
| address | 所在並びに地番 |
| street_address | 住居表示 |
| administration | 行政 |
| lot_size | 地積 |
| current_status_use | 利用の現況 |
| indication_use | 利用状況表示 |
| use_classification | 利用区分 |
| building_structure | 建物構造 |
| facility | 施設 |
| shape_category | 形状区分 |
| width_ratio | 間口（比率） |
| depth_ratio | 奥行（比率） |
| floor_above_ground | 階層（地上） |
| floor_underground | 階層（地下） |
| front_road_classification | 前面道路区分 |
| direction_front_road | 前面道路の方位区分 |
| front_road_width | 前面道路の幅員 |
| front_road_ekimae_classification | 前面道路の駅前区分 |
| pavement_condition_front_road | 前面道路の舗装状況 |
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
| add_floor_area_ratio | 割増容積率 |
| common_site_classification | 共通地点区分 |
| percentage_change_from_previous_year | 対前年変動率 |
| selection_year_bit | 選定年次ビット |


##### Real estate transaction prices (不動産取引価格)

|Field Name| Description |
| ---- | ---- |
| Type | 取引の種類 |
| Region | 地区 |
| MunicipalityCode | 市区町村コード |
| Prefecture | 都道府県名 |
| Municipality | 市区町村名 |
| DistrictName | 地区名 |
| TradePrice | 取引価格（総額） |
| PricePerUnit | 坪単価 |
| FloorPlan | 間取り |
| Area | 面積（平方メートル） |
| UnitPrice | 取引価格（平方メートル単価） |
| LandShape | 土地の形状 |
| Frontage | 間口 |
| TotalFloorArea | 延床面積(平方メートル) |
| BuildingYear | 建築年 |
| Structure | 建物の構造 |
| Use | 用途 |
| Purpose | 今後の利用目的 |
| Direction | 前面道路：方位 |
| Classification | 前面道路：種類 |
| Breadth | 前面道路：幅員（ｍ） |
| CityPlanning | 都市計画 |
| CoverageRatio | 建ぺい率（％） |
| FloorAreaRatio | 容積率（％） |
| Period | 取引時点 |
| Renovation | 改装 |
| Remarks | 取引の事情等 |
