# 🧸 ChinaIPs

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) 

ChinaIPs规则由《RULE GENERATOR 规则生成器》自动生成。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过我国(中华人民共和国)合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则统计

最后更新时间：2022-05-21 21:06:53

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| IP-CIDR | 6216  | 
| IP-CIDR6 | 4168  | 
| TOTAL | 10384  | 


## Stash 

#### 使用说明
- ChinaIPs_Classical.yaml，请使用 behavior: classical。
- ChinaIPs_Classical_No_IPv6.yaml，请使用 behavior: classical。
- ChinaIPs_IP.txt，请使用 behavior: ipcidr-text。

#### 文件区别
- ChinaIPs_Classical.yaml与ChinaIPs_Classical_No_IPv6.yaml的区别在于后者不含IPv6规则，适用纯IPv4网络。
- ChinaIPs_IP.txt与ChinaIPs_IP_No_IPv6.txt的区别在于后者不含IPv6规则，适用纯IPv4网络。

#### 配置建议
- ChinaIPs_IP.txt 单独使用。
- ChinaIPs_IP_No_IPv6.txt 纯IPv4网络，单独使用。
- ChinaIPs_Classical.yaml 单独使用。
- ChinaIPs_Classical_No_IPv6.yaml 纯IPv4网络，单独使用。

#### 规则链接
**MASTER分支 (每日更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ChinaIPs/ChinaIPs_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_Resolve.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6_No_Resolve.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ChinaIPs/ChinaIPs_IP.txt

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Stash/ChinaIPs/ChinaIPs_IP_No_IPv6.txt

**MASTER分支 CDN (每日更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ChinaIPs/ChinaIPs_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_Resolve.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6_No_Resolve.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ChinaIPs/ChinaIPs_IP.txt

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@master/rule/Stash/ChinaIPs/ChinaIPs_IP_No_IPv6.txt

**RELEASE分支 (不定时更新)**

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ChinaIPs/ChinaIPs_Classical.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_Resolve.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6_No_Resolve.yaml

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ChinaIPs/ChinaIPs_IP.txt

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Stash/ChinaIPs/ChinaIPs_IP_No_IPv6.txt

**RELEASE分支CDN (不定时更新)**

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ChinaIPs/ChinaIPs_Classical.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_Resolve.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ChinaIPs/ChinaIPs_Classical_No_IPv6_No_Resolve.yaml

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ChinaIPs/ChinaIPs_IP.txt

https://cdn.jsdelivr.net/gh/blackmatrix7/ios_rule_script@release/rule/Stash/ChinaIPs/ChinaIPs_IP_No_IPv6.txt

## 子规则/排除规则


当前分流规则，未包含其他子规则。

## 数据来源

《ChinaIPs》的数据来自以下链接，如与本项目的《ChinaIPs》规则混合使用，可能会造成规则大量重复。

- https://raw.githubusercontent.com/lhie1/Rules/master/Surge/Surge%203/Provider/Domestic%20IPs.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Extra/ChinaIP.list
- https://raw.githubusercontent.com/Loyalsoldier/surge-rules/release/ruleset/cncidr.txt
- https://raw.githubusercontent.com/Hackl0us/GeoIP2-CN/release/CN-ip-cidr.txt
- https://raw.githubusercontent.com/sve1r/Rules-For-Quantumult-X/develop/Rules/Region/ChinaIP.list
- https://raw.githubusercontent.com/misakaio/chnroutes2/master/chnroutes.txt
- https://raw.githubusercontent.com/Loyalsoldier/clash-rules/release/cncidr.txt


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。