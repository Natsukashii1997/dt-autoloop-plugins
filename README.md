# dt-autoloop-plugins

常浩数字分身给 agent-autoloop 写的插件（方案：digital-twin `docs/agent-autoloop-底座-方案.md` 第 3.2 节）。

- 引擎是私有镜像 `Natsukashii1997/agent-autoloop`，**零补丁**；我们自己的东西都放这里，用 `agent-autoloop add <本地路径>` 装进中台（安装目录的插件优先于内置）。
- 不相对引用引擎源码；个人配置（规则、档位表、Skill、出口脚本）放 digital-twin，不放这里。
- 计划中的插件：`dt-feishu`（飞书只发不收的通道，批 1）、`dt-worktree`（dt-worker 上按任务建 worktree 的启动脚本，批 0C）。

当前是空仓库，批 0C / 批 1 开始往里放。
