# UGREEN 备忘录 · Web Demo

加密的 Web 端交互原型，需密码访问。

🔗 **在线访问**：见 GitHub Pages 链接

## 关于

- Web 端 demo 的密码门版本，整个 demo HTML 用 **AES-256-GCM**（PBKDF2-SHA256，100k 迭代）加密
- 加密密钥从访问密码派生，密码错误直接解密失败、无任何后门
- 源码（`index.html` / `styles.css` / `app.js` / `data.js`）私有，不发到此仓库
- 此仓库只放最终的加密 HTML
