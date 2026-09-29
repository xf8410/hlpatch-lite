# hlpatch-lite

hlpatch 轻量版：基于 xf8410/hlpatch v3.28.2 构建配方，移除画面映射 hook（screen mirror A-stage）的纯数据管道 SO 插件。

与 hlpatch v3.28.2 差异：画面映射注入步不执行（eglSwapBuffers 镜像相关 hook 不存在），其余（3.27.23 cumulative + SIGSEGV guard + 崩溃日志落盘 v3.28.2）一致；插件版本 3.28.2。

风险与时效性声明：偏移随游戏更新可能失效；hook 可能随游戏更新失效；仅供学习研究，其他用途风险自担。
