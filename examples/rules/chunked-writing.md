# Chunked Writing

单次 Write/Edit 限制：
- 常规代码（40-80字符/行）：不超过 300 行
- 短内容（变量名、配置项等）：不超过 800 行
- 超过上限时：
  - 逻辑代码：先 Write 前 300 行，再 Edit 追加，每次追加前 Read 末尾10行确认衔接
  - 重复/模式化内容（i18n、XML、SVG、config、>500行）：写生成脚本再执行

Write/Edit 报 "missing parameter" = 输出被截断，立即减半块大小重试。
