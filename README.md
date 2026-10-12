# huangshichao.github.io

Personal homepage of **Shichao Huang**

访问地址：<https://huangshichao.github.io>

## 内容

| 页面 | 出处 |
|------|------|
| [面向数据中心 HVAC 的边缘—云协同深度强化学习多目标优化](posts/data-center-hvac-edge-cloud-drl.html) | *Sensors* (MDPI), 2026 · CC BY 4.0 |
| [基于矢量图形渲染的安全浏览器设计与实践](posts/secure-browser-based-on-vector-graphics-rendering.html) | CICED 2026 · 出版方 IEEE |

## 目录结构

```
.
├── index.html                                    # 主页
├── posts/
│   ├── data-center-hvac-edge-cloud-drl.html
│   └── secure-browser-based-on-vector-graphics-rendering.html
├── assets/css/style.css                          # 全站样式（响应式 / 深色模式 / 打印）
├── .nojekyll                                     # 关闭 Jekyll 处理，直接静态托管
└── .gitignore
```

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 部署

仓库 `main` 分支根目录即为站点根目录，GitHub Pages 直接托管，无需构建步骤。
