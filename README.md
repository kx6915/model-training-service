# 模型训练服务 · Model Training Service

模型微调训练服务的前端页面（纯静态，无后端）。

- 首页：高级宣传页（Hero + 四步流程 + CTA）
- 训练页：智能参数推荐（按 11 月三轮真实实验规则推荐：39 条样本未通过；183 条全参数 fp32 / lr 2e-5 / 3 epoch 通过 3/3 验收）+ 三个训练方式（LoRA 微调 / 全参数微调 / 从零预训练），各自上传校验、参数表单、配置规格单、任务队列
- 后端尚未接入：提交只进本地任务队列，模型下载未启用

## 在线访问（GitHub Pages）

仓库建好后，在 GitHub 网页端打开 **Settings → Pages → Build and deployment → Source 选择 Deploy from a branch → Branch 选 main、文件夹选 /(root) → Save**，几分钟后访问：

https://kx6915.github.io/model-training-service/

## 本地打开

直接用浏览器打开 `index.html` 即可。
