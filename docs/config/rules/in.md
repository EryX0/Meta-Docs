## IN-TYPE

匹配流量入站的类型

```{.yaml linenums="1"}
rules:
- IN-TYPE,INNER,proxy
```

### 支持的类型

HTTP/SOCKS/TUN/TPROXY/REDIR/INNER

!!! note
    INNER 为 providers 的下载请求

## IN-USER

匹配入站用户名,目前仅vmess入站支持配置用户名

```{.yaml linenums="1"}
rules:
- IN-USER,meta,DIERCT
```

## IN-NAME

匹配入站名称

```{.yaml linenums="1"}
rules:
- IN-NAME,ss,PROXY
```

关于[入站](../inbound/index.md)
