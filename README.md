# Qxlazydan Quantumult X 配置

懒人自用 Quantumult X 配置，借鉴了各路大佬的规则，整合广告拦截、分流、策略组与常用解锁功能。  
作者：[@jorgut](https://github.com/Jorgut)  
更新日期：2025-09-01  

---

## 🔗 下载直链

将下方直链粘贴到 Quantumult X → Profile → Download from URL 中即可导入：

https://raw.githubusercontent.com/Jorgut/UncleDan-QX-CONFIGS/master/Lazydan2025.conf

markdown
Копировать код

---

## 🍎 Apple News 解锁

本配置已包含 **Apple News 必要分流**，支持在非美国地区（如中国大陆）使用。  

### 使用步骤  
1. **注册美区 Apple ID**  
   - 在 Apple 官网创建一个美国地区 ID，或使用已有的美区账号。  

2. **修改设备地区**  
   - 前往「设置」>「通用」>「语言与地区」，将地区改为「美国」。  

3. **下载 Apple News 应用**  
   - 登录美区 Apple ID，在 App Store 搜索并下载 **Apple News**。  

4. **使用代理节点**  
   - 在 Quantumult X 中选择美国节点，确保能够正常访问。  

5. **开启飞行模式后连 Wi-Fi**  
   - 避免使用中国运营商网络，减少区域检测。  

6. **打开地图应用**  
   - 打开系统自带的 **Maps**，等待几秒钟，让地图数据切换到国际版（如 TomTom）。  

7. **访问 Apple News**  
   - 返回 Apple News 应用，即可正常浏览内容。  
   - 如遇问题，可尝试重启应用或重复上述步骤。  

⚠️ 注意：Apple News 的可用性可能因系统更新或政策调整而变化，建议定期关注最新信息。  

---

## 📖 其他使用说明

1. **证书 (MitM)**  
   - 请在 Quantumult X → 设置 → MitM 中手动生成证书，并在系统设置中安装与信任。  
   - 仓库中的 `passphrase` 与 `p12` 已留空，仅提供占位，不包含真实证书。  

2. **策略组**  
   - AI / Claude / Copilot / Gemini → AI 服务专用策略组。  
   - 🎬 YouTube、📺 Netflix、🍎 苹果服务 → 常用流媒体分流。  
   - 🕹 终极清单 → 兜底策略组。  

3. **复写 (Rewrite)**  
   - 已集成 Reddit、YouTube、小红书、Spotify、微博等去广告与解锁脚本。  
   - 建议保持 `update-interval=172800`，即两天更新一次。  

4. **分流 (Filter)**  
   - 国内 IP / 国内网站直连，海外服务按策略组分流。  

---

## ⚠️ 注意事项

- 本仓库公开分享的配置文件中 **不包含订阅链接与证书材料**，请自行添加。  
- 请勿将个人的代理订阅地址 (`server_remote`) 直接提交到公开仓库，以免泄露账号。  
- 使用时请检查 Quantumult X 日志，确认无 `Wrong grammar` 报错。  

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
