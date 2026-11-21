First Call — 五页完整前端源码

解压后打开 First_Call_Home.html。五个 HTML 必须保持在同一文件夹。
Home / Services / Products / About / Contact 导航已连接，询价按钮进入 Contact 表单。

Contact 表单：姓名、位置、维修描述必填；邮箱或电话至少填一项。
可以选择/移除最多5张照片，每张10MB以内。照片仅在本机预览，不会上传。
Request a Quote 打开邮件应用并填写邮件正文，用户必须自行添加照片附件并发送。
没有在线收件后台，不会显示虚假的“发送成功”。若邮件应用未配置，请直接拨号或发邮件。
要实现网页直接收件及附件上传，需要另行配置表单服务或服务器端接口，当前代码不包含该部分。

About 案例：搜索 First_Call_About.html 中的 const repairCases，填写各分类的 before、after、description。
例如 before: 'images/seat-before.jpg', after: 'images/seat-after.jpg'。
将照片放入同目录的 images 文件夹，上线时一并上传；左 Before / 右 After。
每分类支持一组照片，目前保留空白占位。

代码为原生 HTML/CSS/JavaScript，无需安装依赖。图片和 Logo 沿用设计素材，正式上线建议替换高清原件。

点击进入：<a href="https://leatherosolutions.com" target="_blank" rel="noopener noreferrer">First Call Reconditioning</a>
