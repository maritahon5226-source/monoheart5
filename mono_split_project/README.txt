Mono split project

文件结构：
- index.html：页面骨架
- style.css：从原 HTML 拆出的全部样式
- script.js：从原 HTML 拆出的聊天、线下剧情、API 等 JS 逻辑
- assets/：从原 HTML 的 base64 图片资源拆出的静态资源

上传部署时请保持这些文件在同一个文件夹里，不要只上传 index.html。
入口文件仍然是 index.html。
