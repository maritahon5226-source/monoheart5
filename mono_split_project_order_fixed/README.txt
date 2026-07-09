Mono split project - order fixed

上传部署时必须保持以下文件同一层级：
index.html
style.css
script.js
assets/

本版修复：
1. style.css 放到 Tailwind 和字体 CSS 后面加载，避免 Tailwind 覆盖自定义样式导致格式错乱。
2. style.css / script.js 增加版本参数，避免手机/PWA 缓存旧的错乱文件。
3. 保留 assets 相对路径。

不要只上传 index.html。
