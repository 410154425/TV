自用
config.py：
source_file：模板文件，默认值：demo.txt
final_file：生成文件，默认值：result.txt
favorite_list：关注频道名称列表
favorite_page_num：关注频道获取分页数量，默认值：5
default_page_num：常规频道获取分页数量，默认值：3
urls_limit：接口数量，默认值：15
response_time_weight：响应时间权重值，默认值：0.5
resolution_weight：分辨率权重值，默认值：0.5
.github/workflows/main.yml：
如果您想修改更新频率（默认 12 小时），可修改 on:schedule:- cron 字段
result.txt 为更新后的直播源接口文件，source.json 为数据源文件（目前仅作分享使用）

建议采用代理的方式访问直播源与数据源文件（xxx 为您的仓库路径）：

https://mirror.ghproxy.com/raw.githubusercontent.com/xxx/result.txt
https://mirror.ghproxy.com/raw.githubusercontent.com/xxx/source.json
