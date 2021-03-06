##### 坐标系

+ 地理坐标系
+ 投影坐标系

##### 比例尺

> 图上距离/实际距离

二维地图主要非为矢量地图和瓦片地图



##### openlayer核心类和组件

| Map         | 地图容器，客家在各类地图与功能空间                           |
| ----------- | ------------------------------------------------------------ |
| View        | 地图视图，控制地图缩放等基本交互，地图投影坐标系、地图中心点、分辨率、旋转角度等 |
| Layers      | 图层，由子类实例加载地图数据，必须结合图层数据源             |
| Source      | 图层数据源                                                   |
| Format      | 数据解析类，用于读/写各种格式数据，支持多种数据格式，geoJSON，GML，XML，WKT，WFS |
| Geometry    | 地理空间对象几何实体                                         |
| Feature     | 地图要素                                                     |
| Overlay     | 叠加层，即叠加到地图上显示的要素                             |
| Controls    | 控件类                                                       |
| Interacting | 地图交互控件类                                               |
| Style       | 样式类                                                       |
| Projections | 地图投影自定义类                                             |
| Renderer    | 渲染器，支持Canvas、Dom、WebGL三种渲染方式                   |

