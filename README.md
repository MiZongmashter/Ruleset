# Ruleset

个人代理规则集。

| 规则集 | 文件 | Raw 订阅地址 |
| --- | --- | --- |
| Apple Intelligence | [Apple Intelligence.list](Ruleset/Apple%20Intelligence.list) | `https://raw.githubusercontent.com/MiZongmashter/Ruleset/main/Ruleset/Apple%20Intelligence.list` |
| Autodesk | [Autodesk.list](Ruleset/Autodesk.list) | `https://raw.githubusercontent.com/MiZongmashter/Ruleset/main/Ruleset/Autodesk.list` |
| NOProxy | [NOProxy.list](Ruleset/NOProxy.list) | `https://raw.githubusercontent.com/MiZongmashter/Ruleset/main/Ruleset/NOProxy.list` |

Autodesk 规则只匹配 Autodesk、ADSK 和 ShotGrid 品牌域名，不包含共享云/CDN、通用登录或统计服务的整站后缀，也不按域名关键词匹配。第三方下载、授权和单点登录依赖由客户端的其他规则或默认策略处理；如需指定出口，应根据实际连接记录添加已核实的专用主机，避免将整家云服务商归入 Autodesk。
