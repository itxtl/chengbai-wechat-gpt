<h1 align="center">欢迎使用 wechat-chatgpt 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/badge/License-ISC-yellow.svg" />
  </a>
  <a href="https://twitter.com/fuergaosi" target="_blank">
    <img alt="Twitter: fuergaosi" src="https://img.shields.io/twitter/follow/fuergaosi.svg?style=social" />
  </a>
  <a href="https://discord.gg/8fXNrxwUJH" target="blank">
    <img src="https://img.shields.io/discord/1058994816446369832?label=Join%20Community&logo=discord&style=flat-square" alt="join discord community of github profile readme generator"/>
  </a>
</p>

> 在微信上迅速接入 ChatGPT，让它成为你最好的助手！  
> [English](README.md) | 中文文档

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/dMLG70?referralCode=bIYugQ)

## 🌟 功能点

- [x] 通过 [wechaty](https://github.com/wechaty/wechaty) 和 [官方 API](https://openai.com/blog/introducing-chatgpt-and-whisper-apis)，将 ChatGPT 接入微信
- [x] 加入了持续对话的功能
- [x] 通过 Railway 进行部署

## 🚀 使用
- [在 Railway 部署](#使用railway进行部署)(PaaS, 免费, 稳定, ✅推荐)
- [在 Fly.io 部署](#通过flyio进行部署)(PaaS, 免费, ✅推荐)
- [使用 Docker 部署](#通过docker使用)(自托管, 稳定, ✅推荐)
- [使用 Docker Compose 部署](#通过docker-compose使用)(自托管, 稳定, ✅推荐)
- [使用 NodeJS 部署](#使用nodejs运行)

## 使用Railway进行部署
> Railway 是一个免费的 PaaS 平台，5刀以内的账单免费或者每个月500小时的运行时间
1. 点击 [Railway](https://railway.app/template/dMLG70?referralCode=bIYugQ) 按钮，进入 Railway 部署页面
2. 点击 `Deploy Now` 按钮，进入 Railway 部署页面
3. 填写 仓库名称和 `OPENAI_API_KEY`(需要连接 GitHub 账号)
4. 点击 `Deploy` 按钮
5. 点击 `View Logs` 按钮，等待部署完成

## 感谢支持 🙏

如果这个项目对你产生了一点的帮助，请为这个项目点上一颗 ⭐️