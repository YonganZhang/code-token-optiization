# Token Optimization Plan

## 分层策略
- 每条命令/工具调用/网络请求都要遵守 → Rule（≤10行）
- 特定任务触发 → Skill description 触发（省 Rule 固定成本）
- 详细方法论 → 加载 skill `token-optimization`

## 持久日志
- 推进性交互（任务/问题/决策）→ 追加到 `docs/plan/plan.md`
- 闲聊/简单查询 → 不记录
- 会话开始若 plan.md 存在 → 先读取恢复上下文
