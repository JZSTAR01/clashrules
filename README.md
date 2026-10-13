# clashrules

个人自用 clash 远程规则（subconverter 远程配置：`remoteconfig.ini`）。

## 规则文件

| 文件 | 策略组 | 说明 |
| --- | --- | --- |
| Reject.list | REJECT | 拦截 |
| DIRECT.list | DIRECT | 局域网、路由器管理页、测速/IP 查询、学术站点 |
| Bilibili.list | Bilibili | 哔哩哔哩（含港澳台） |
| Openai.list | Openai | ChatGPT / OpenAI / Sora |
| AI.list | AI | Claude、Gemini、Copilot、Grok、Perplexity、Cursor、Hugging Face 等 |
| Netflix.list | Netflix | Netflix |
| Apple.list | Apple | Apple 服务 |
| Paypal.list | Paypal | PayPal |
| Proxy.list | Proxies | 常用境外站点（含 Telegram、YouTube、GitHub、Discord、X、TikTok、Spotify） |
| Domestic.list | Domestic | 国内站点，之后由 GEOSITE,CN / GEOIP,CN 兜底 |

未在 `remoteconfig.ini` 中引用、按需自取：Disney.list、Pikpak.list、BaiduPan.list、Gamencn.list（暴雪非国服）。

## 来源

部分规则合并自 [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)，每个文件头部注明了更新日期。
