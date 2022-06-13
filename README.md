# DDRecorder 改
Ver 0614
 Headless全自动B站直播录播、切片、上传一体工具

原Repo：https://github.com/AsaChiri/DDRecorder
 
 - 补上了原版遗漏的依赖
 - 新增了上传线路选择的设置
 - 新增了动态的设置
 - Dockerfile指定时区（Asia/Shanghai）。防止docker内时区错误导致录播日期偏移。
 
 设置改动部分:
 
 ### 全局设置（root部分）

- line：上传线路。默认 AUTO。 详见biliup项目。目前可手动切换为bda2, kodo, ws, qn。
- threads：上传并发数.默认：3。
- dynamic：动态内容。默认为空。
