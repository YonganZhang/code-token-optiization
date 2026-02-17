# Web Search Rules

- 默认搜索工具：优先使用内置 WebSearch，直接可用、无需额外 MCP。
- 备选/增强：Tavily MCP 在以下场景启用：
  - WebSearch 不可用或返回空结果时，作为 fallback
  - 需要强力搜索时，与 WebSearch 一起并行使用
- 其他 fallback：GitHub MCP 或 WebFetch（已知 URL）。
