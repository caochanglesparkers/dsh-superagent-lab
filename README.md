# dsh-superagent-lab

DSH `dsh-session-superagent` 的端到端测试仓库。

这个仓库本身没有业务代码，它存在的唯一目的是给「主理鱼」一个可盯的目标：
每次在这里提 issue / 开 PR，插件的 watcher 都会轮询到，然后唤醒对应的 DSH 会话。

## 用途

- 验证 `watch_start` / `watch_stop` / `watch_status` 的完整链路
- 验证 `watch_doctor` 的自检结果
- 验证唤醒消息与 `AGENTS.md` 规则传递

## 规则

处理规则写在 [AGENTS.md](./AGENTS.md)。
