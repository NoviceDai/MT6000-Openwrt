# MT6000-Openwrt-compile-workflow
!! important !!
   增加任何插件后都可能额外增加支持库，当删除插件时，需要检查是否有依赖库，如果有，需要手动删除。
源代码：https://github.com/openwrt/openwrt.git   

V0 Openwrt 24.10 compile action  for MT6000
* v0.01 20250331  test
* v0.02 20250331  delete dnsmasq (conflict with dnsmasq-full)
* v0.03 20250331  add passwall, wol
* v0.1  20250410  add luci-app-dockerman\docker  dig\nslookup 

V1 upgrade to  Openwrt 25.12.2  
* v1.1 edit workflows 
* v1.2 remove docker add luci themes 
* v1.3 add passwall plugin -- * xray\hysteria 
* v1.4 passwall2   + adguardhome 
* v1.5 passwall with xray hysteria / delete passwall2/smartdns 

V2 upgrade to  Openwrt 25.12.5 
* v2.1 only update   

V3 upgrade to  Openwrt 25.12.6  (2026/10/27)
* v3.1 update  & add luci-app-command
  