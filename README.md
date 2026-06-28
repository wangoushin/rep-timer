
# 节奏计时器 / RepTimer

一个简单的本地锻炼节奏计时器，适合需要按照「保持 → 放松 → 重复」节奏进行的训练，例如腹肌静态收缩、平板支撑变体、拉伸、盆底肌训练等。

<img height="480" alt="QQ20260629-032403" src="https://github.com/user-attachments/assets/c6ef13bf-ab6f-457a-b3ed-f44e8cc9b03a" />
---

## 在线 Demo

[点击这里打开在线 Demo](https://wangoushin.github.io/rep-timer/)

## 功能特点

* 自定义保持秒数
* 自定义放松秒数
* 自定义每组次数和组数
* 支持多个训练模板
* 每个模板可单独保存设置
* 支持备注输入
* 数据自动保存到浏览器 LocalStorage
* 无需后端服务，直接打开 HTML 文件即可使用

---

## 使用场景

这个工具适合以下类型的训练：

* 腹肌静态收缩
* 平板支撑变体
* 拉伸保持训练
* 盆底肌训练
* 康复类节奏训练
* 任何需要「保持几秒 → 放松几秒 → 重复多次」的训练

---

## 使用方法

1. 设置保持秒数
2. 设置放松秒数
3. 设置每组次数
4. 设置组数
5. 根据需要填写备注
6. 点击「开始」进行训练

---

## 模板功能

你可以创建多个训练模板，例如：

* 腹肌训练
* 平板支撑
* 拉伸训练
* 盆底肌训练

每个模板都会保存自己的设置：

* 保持秒数
* 放松秒数
* 每组次数
* 组数
* 备注

所有数据都会保存在浏览器的 LocalStorage 中。

---

## 本地运行

下载或克隆本仓库后，直接用浏览器打开 `index.html` 文件即可。

```bash
git clone https://github.com/your-username/rep-timer.git
cd rep-timer
```

然后双击打开：

```text
index.html
```

---

## 项目结构

```text
rep-timer/
├── index.html
├── README.md
└── LICENSE
```

---

## 技术栈

* HTML
* CSS
* JavaScript
* LocalStorage

不依赖任何前端框架。

---

## 数据保存

本项目使用浏览器的 LocalStorage 保存训练模板数据。

数据只保存在当前浏览器中，不会上传到服务器。

如果清除浏览器缓存或 LocalStorage，保存的模板数据可能会被删除。

---

## 许可证

MIT License

Copyright (c) 2026 wangoushin

---

## 作者

wangoushin
