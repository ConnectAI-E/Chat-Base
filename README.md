<a href="https://chatbase.connectai.site/">
  <img width="100%" alt="image" src="https://github.com/ConnectAI-E/TalkBase/assets/50035229/6edf828f-ff44-41b5-b3f4-4e520d3e6432">
</a>
<br/>
<br/>


<p align="center">
    <a href="https://github.com/connectai-e/awesome-basescript">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="License" />
  </a>
  <a href="https://github.com/connectai-e/Chat-Calculator/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/connectai-e/Chat-Calculator?label=license&logo=github&color=f80&logoColor=fff" alt="License" />
  </a>
  <a href="https://github.com/connectai-e/Chat-Calculator"><img src="https://img.shields.io/github/stars/connectai-e/Chat-Calculator?style=social" alt="Chat-Calc's GitHub repo"></a>
</p>


<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#deploy-your-own"><strong>Deploy Your Own</strong></a> ·
  <a href="#quick-start"><strong>Setting Up Locally</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#contributing"><strong>Contributing</strong></a> ·
  <a href="#license"><strong>License</strong></a>
</p>
<br/>

## Introduction

TalkBase is an open-source AI chatbot that uses [TypeChat](https://github.com/microsoft/TypeChat) and the [Vercel AI SDK](https://sdk.vercel.ai/docs) to interact with natural language.


🐵 Easily enter data by natural language , with the requirements table field meta and descriptions.
![chatbasegif](https://github.com/ConnectAI-E/Chat-Base/assets/110169811/3f69a25a-f66b-450a-a478-1986debd37b3)


🙈 automatically describe the purpose of the table and give text suggestions for entering data
![quickShow](https://github.com/ConnectAI-E/TalkBase/assets/50035229/10ddf80a-c504-4c42-b516-d70cf9e50268)

## Quick Start

1️⃣  open the grayscale qualification for base extension

https://applink.feishu.cn/client/chat/chatter/add_by_link?link_token=c55n4142-fce8-4792-b851-f92c9c7d8300
  
2️⃣  copy talk-base online link to the extension script address 
```
https://chatbase.connectai.site/
```
3️⃣ start to chat-base ~





## Dev Local

To set up talkBase locally, you'll need to clone the repository and set up the following environment variables:

- `OPENAI_API_KEY` – your OpenAI API key (you can get one [here](https://platform.openai.com/account/api-keys))


1️⃣ clone deme
```
git clone https://github.com/ConnectAI-E/BaseScript-LinkPreview
pnpm install
pnpm dev
```
2️⃣ copy talkbase dev link to the extension script address
```
http://localhost:5173/
```

## Deploy your own

You can deploy your own version of TalkBase with one-click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ConnectAI-E/TalkBase&env=OPENAI_API_KEY&project-name=chat-calc&repository-name=Chat-Base)
</details>




## Tech Stack

ChatH is built on the following stack:

- [Next.js](https://nextjs.org/) –framework
- [TypeChat](https://github.com/microsoft/TypeChat) –llm framework
- [BaseScript](https://github.com/ConnectAI-E/Awesome-BaseScript) -lark base script plugin
- [Vercel](https://vercel.com) - deployments
- [TailwindCSS](https://tailwindcss.com/) – css styles


## License

Licensed under the [MIT license](https://github.com/connectai-e/chat-base/blob/main/LICENSE.md).
