# trends 获取商品列表

# 地址
POST /trends

# 参数
`class` 商品三级分类；可选；如：622,333,555；  
`url` 商品列表地址；可选；  
`excludes` 排除筛选；可选；用英文逗号分隔，如：颜色,人群；  
`page` 返回页数总和的数据；可选；默认5；  
**class 和 url 有且只有其中一个**  

#返回
````
[
  "342342424",
  "234244354",
  "4646464747",
  "567657575",
  ...
]
````
