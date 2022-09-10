# 使用方法
1. 安装依赖项
2. 修改run.py中的since、till为需要的区间
3. python3 run.py


# 开发者注意
1. 运行期间会生成scan_dump-{since.dta()}-{till.date()}. dump和records_dump-{since.date()}-{till.date()}. dump文件， 前者是从gitlab获取提交记录的中间结果， 后者则是按提交者、 单号归组后的中间结果。 保存中间结果是为了加快排bug时测试的时间。
