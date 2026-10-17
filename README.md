# 证研 · 投研观点证据核验助手

公开体验地址：https://yling110500.github.io/evidence-desk/

面试演示作品，材料均为虚构。当前为明确标注的人工参考演示，提供观点A、观点B和临时查询三个案例。真实AI核验还需独立后端与模型凭证。

- index.html：可直接由GitHub Pages托管的完整前端，不含密钥。
- design.html：产品设计思路文档。
- evidence-desk-source.zip：完整源码、后端接口、测试与部署说明，不含凭证或私人云端资产标识。

Pages使用main分支根目录发布。源码解压后可用Node.js 22.9+运行；18项自动化测试通过。

更新页面：在源码目录运行 node scripts/build-single.mjs，将github-publish中的index.html和design.html上传到仓库。设置PUBLIC_API_BASE后可构建连接真实后端的版本，密钥只能留在后端。
