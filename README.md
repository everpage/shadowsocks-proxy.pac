# shadowsocks-proxy.pac
fq 命令 依赖

**fq 命令:**

```bash
$ sudo fq a
```

采用 `https://everpage.github.io/shadowsocks-proxy.pac/shadowsocks-proxy.pac` 作为 pac ，否则使用本地 pac 则依赖于 Nginx ，Nginx不启动就不fq了。

Mac -> 系统偏好设置 -> 网络 -> 高级 -> 代理 -> 自动代理配置（勾选） -> URL: `https://everpage.github.io/shadowsocks-proxy.pac/shadowsocks-proxy.pac`

> 实测采用 `file:///usr/local/etc/shadowsocks-proxy.pac` 这种虽然 Chrome 可用，但是用久了会抽风，不稳定！而且不适用于 Safari 浏览器！
