# Qxlazydan Quantumult X 配置

懒人自用 Quantumult X 配置，借鉴了各路大佬的规则，整合广告拦截、分流、策略组与常用解锁功能。  
作者：[@jorgut](https://github.com/Jorgut)  
更新日期：2025-09-01  

---

## 🔗 下载直链

将下方直链粘贴到 Quantumult X → Profile → Download from URL 中即可导入：

```
https://raw.githubusercontent.com/Jorgut/UncleDan-QX-CONFIGS/master/Lazydan2025.conf
```

---

## 📖 使用说明

1. **Profile 导入**  
   - Quantumult X → 配置文件 → 从 URL 下载  
   - 粘贴直链，保存即可。

2. **证书 (MitM)**  
   - 请在 Quantumult X → 设置 → MitM 中手动生成证书，并在系统设置中安装与信任。  
   - 仓库中的 `passphrase` 与 `p12` 已留空，仅提供占位，不包含真实证书。

3. **策略组说明**  
   - AI / Claude / Copilot / Gemini → AI 服务走专用策略组。  
   - 🎬 YouTube、📺 Netflix、🍎 苹果服务 → 常用流媒体分流。  
   - 🕹 终极清单 → 兜底策略组。  

4. **复写 (Rewrite)**  
   - 已集成 Reddit、YouTube、小红书、Spotify、微博等常见去广告与解锁脚本。  
   - 保持远程脚本更新，建议 `update-interval=172800` (两天)。

5. **分流 (Filter)**  
   - 来自 [blackmatrix7](https://github.com/blackmatrix7/ios_rule_script) 与 [ddgksf2013](https://github.com/ddgksf2013) 的规则集。  
   - 国内 IP / 国内网站直连，海外服务按策略组分流。  

---

## ⚠️ 注意事项

- 建议保持仓库为 **公开配置 + 本地证书**，避免泄露隐私。  
- 若需存放证书，请将仓库改为 **私有**。  
- 导入后请检查 Quantumult X 日志，确认无 `Wrong grammar` 报错。  
- 策略组名称需与 `force-policy` 保持完全一致（含 Emoji 和中文）。  

---

## 🙏 鸣谢

本配置参考并使用了以下项目与作者的脚本：

- [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)  
- [ddgksf2013/Rewrite](https://github.com/ddgksf2013/Rewrite)  
- [KOP-XIAO/QuantumultX](https://github.com/KOP-XIAO/QuantumultX)  
- 其他开源贡献者  

---

## 📬 反馈

问题或建议请提交 Issue，或联系：  
- 邮箱：ins.stu@outlook.com  
- 微信公众号：ArchIntera／界构实验室  
