# 使用说明

在 VPS 上使用 root 用户执行。

## 安装 / 更新

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/igweek/singbox-manual/refs/heads/main/install.sh)
```

已安装时，选择 `1` 更新脚本，再按提示决定是否更新内核。

## 打开面板

```bash
sb
```

- 添加节点：选 `1`，按提示填写，完成后复制链接到客户端。
- 查看节点：选 `4`。
- 启动、停止、重启：选 `6`。
- 更新：选 `7`。
- 卸载：选 `9`。

节点端口还需在 VPS 服务商的安全组中放行；Hysteria2、TUIC 要放行 UDP。
