# tvbox-json
tvbox接口配置部署代码
使用说明：
部署步骤：
登录 Cloudflare → Workers → 创建 Worker
粘贴上述work.josn代码 → 保存并部署
添加自定义域名绑定（如api.yourdomain.com）
访问方式：
通过绑定的域名直接访问（如https://api.yourdomain.com），浏览器将显示完整 JSON 内容。
响应优化：
已设置Content-Type为 JSON 格式
添加跨域支持（Access-Control-Allow-Origin）
