
<h1 align="center">免费GPT-API/ 免费DeepSeek-API</h1>


国内中转加速/直连，无需代理 适配官方协议，无需复杂转换。[登录我们的官网注册后获取自定义数量apikey和购买付费key](https://api.rcouyi.com/register?aff=5kMw)


[快速开始](#如何使用) / [API文档](https://chatanywhere.apifox.cn/) / [申请内测免费Key](https://api.chatanywhere.org/v1/oauth/free/render) / [支持付费Key](https://api.chatanywhere.tech/#/shop/) / [服务可用性](https://status.chatanywhere.tech/)

[![](https://status.chatanywhere.org/api/badge/6/uptime/24?labelPrefix=GPT:)](https://status.chatanywhere.tech/)
[![](https://status.chatanywhere.org/api/badge/10/uptime/24?labelPrefix=GPT-CA系列:)](https://status.chatanywhere.tech/)

[![](https://status.chatanywhere.org/api/badge/8/uptime/24?labelPrefix=Claude:)](https://status.chatanywhere.tech/)
[![](https://status.chatanywhere.org/api/badge/3/uptime/24?labelPrefix=Gemini:)](https://status.chatanywhere.tech/)
[![](https://status.chatanywhere.org/api/badge/4/uptime/24?labelPrefix=Deepseek:)](https://status.chatanywhere.tech/)


## 隐私声明

该项目高度重视隐私，致力于保护其用户的隐私。该项目不会以任何方式收集、记录或存储用户输入的任何文本或由 OpenAI 服务器返回的任何文本。该项目不会向 OpenAI 或任何第三方提供有关 API 调用者的身份的任何信息，包括但不限于 IP 地址和用户代理字符串。

但OpenAI官方会根据其[数据使用政策](https://platform.openai.com/docs/data-usage-policies)保留 30 天的数据。


## 功能亮点  
1. 支持多种顶级大模型，如 GPT、DeepSeek、Claude、Gemini 和 Grok 等。  
2. 免费版提供 GPT-4o 和 GPT-4.1 每日 5 次调用；DeepSeek-R1 和 DeepSeek-V3 每日 30 次；GPT-4o-mini、GPT-3.5-turbo、GPT-4.1-mini 和 GPT-4.1-nano 每日 200 次。  
3. 接口完全遵循官方标准，完美兼容各种软件和插件。  
4. 支持流式数据响应。  
5. 国内线路使用动态加速技术，性能远超通过代理访问官方服务的体验。  
6. 无需翻墙，国内环境即可直接使用。  
7. 个人用户免费使用，无任何费用。  
8. 统一采用 OpenAI 标准协议，切换其他厂商模型仅需修改模型名称，接入简单快捷。  

## 🚩使用须知  

❗️*若出现无响应或错误提示，请访问 [官网首页>底部](https://api.rcouyi.com) 检查服务状态，以协助排查问题。*  

❗️**免费 API Key 仅限个人非商业用途、教育或非营利性科研项目。严禁用于商业用途或大规模训练商业模型！如需用于科研模型训练，请提前通过群组联系我们。**  

❗️本系统仅供内部测试和评估，商业用途或公开使用需自行承担相应风险


| API 类型        | 请求限制                          | 说明                                                                 |
|-----------------|-----------------------------------|----------------------------------------------------------------------|
| 免费 API Key    | 200 请求/天/IP & Key             | GPT 和 Embedding 分开计算，各 200 次。同一 IP 下多个 Key 的总请求数不超过 200 次；同一 Key 在多个 IP 下的总请求数不超过 200 次。 |
| 付费版 API      | 无请求限制                       | 付费版 API 不受免费版请求限制。                                       |

## 免费测试使用

- 首先，**🚀[申请领取内测免费API Key](https://api.chatanywhere.org/v1/oauth/free/render)**
- 免费版支持deepseek, gpt-3.5-turbo, embedding, gpt-4o-mini, gpt-4o。
- 使用测试区服务**转发Host1: `https://api.chatanywhere.tech` (国内中转，延时更低)**
- 使用测试区服务**转发Host2: `https://api.chatanywhere.org` (国外使用)**


| 项目说明                     | 内容                                                                 |
|-----------------------------|----------------------------------------------------------------------|
| API 服务扩容                 | 将根据使用量定期进行扩容，以确保服务稳定性，前提为未受到官方限制。     |
| API Key 使用方式             | 用于转发 API，需将 Host 配置为 `api.chatanywhere.tech`（国内首选）或 `api.chatanywhere.org`（国外使用）。 |


## 付费版API
- 纯公益提供免费Key显然不是能持久运营下去的方案，所以我们引入付费API Key维持项目的日常开销，以促进项目的良性循环，还望大家理解。
- [购买付费Key](https://api.rcouyi.com/register?aff=5kMw)
- [付费版价格表](https://api.rcouyi.com/pricing)

1. 支持**更稳定更快速的GPT4 API**，GPT4体验更好，无限使用，价格低于官方，充值更便捷。
2. 同官网计费策略，流式问答使用tiktoken库准确计算Tokens，非流式问答直接使用官方返回Tokens用量计费。
3. 新用户注册赠送＄0.2。余额不会过期，永久有效。根据用户反馈30块钱个人中度使用gpt-4o-mini估计能用半年。
4. 所有的接口（包括免费版本）都保证转发自OpenAI或Azure官方接口，非peo、plus等不稳定方案或逆向方案，无水分，不掺假，保证稳定性。

## 付费版支持模型
| **模型（Model）** | **请求（Input）** | **回答（Output）** | **是否支持** | **特点** |
| --- | --- | --- | --- | --- |
| o3 | 0.08 / 1K Tokens | 0.32  / 1K Tokens | 支持 | 为数学、科学、编码、视觉推理任务和技术写作设定了新的标准。 指向o3-2025-04-16|
| o3-2025-04-16 | 0.08 / 1K Tokens | 0.32   / 1K Tokens | 支持 | 为数学、科学、编码、视觉推理任务和技术写作设定了新的标准。 |
| o4-mini | 0.0088 / 1K Tokens | 0.0352  / 1K Tokens | 支持 | 为数学、科学、编码、视觉推理任务和技术写作设定了新的标准。 指向o4-mini-2025-04-16|
| o4-mini-2025-04-16 | 0.0088 / 1K Tokens | 0.0352  / 1K Tokens | 支持 | 为数学、科学、编码、视觉推理任务和技术写作设定了新的标准。 |
| gpt-4.1 |  0.014 / 1K Tokens | 0.056   / 1K Tokens | 支持 | OpenAI最新推出的模型 在编码、指令跟踪和长上下文方面都有重大改进1M输入32k输出 指向gpt-4.1-2025-04-14 |
| gpt-4.1-2025-04-14 | 0.014 / 1K Tokens | 0.056  / 1K Tokens | 支持 | OpenAI最新推出的模型 在编码、指令跟踪和长上下文方面都有重大改进1M输入32k输出|
| gpt-4.1-mini | 0.0028 / 1K Tokens | 0.0112  / 1K Tokens | 支持 | OpenAI最新推出的模型 在编码、指令跟踪和长上下文方面都有重大改进1M输入32k输出 指向gpt-4.1-mini-2025-04-14 |
| gpt-4.1-mini-2025-04-14 | 0.0028 / 1K Tokens | 0.0112  / 1K Tokens | 支持 | OpenAI最新推出的模型 在编码、指令跟踪和长上下文方面都有重大改进1M输入32k输出|
| gpt-4.1-nano | 0.0007 / 1K Tokens | 0.0028  / 1K Tokens | 支持 | OpenAI最新推出的模型 在编码、指令跟踪和长上下文方面都有重大改进1M输入32k输出 指向gpt-4.1-nano-2025-04-14 |
| gpt-4.1-nano-2025-04-14 | 0.0007 / 1K Tokens | 0.0028  / 1K Tokens | 支持 | OpenAI最新推出的模型 在编码、指令跟踪和长上下文方面都有重大改进1M输入32k输出|
| gpt-3.5-turbo | 0.0035 / 1K Tokens | 0.0105 / 1K Tokens | 支持 | 默认模型，等于gpt-3.5-turbo-0125|
| gpt-3.5-turbo-1106 | 0.007 / 1K Tokens | 0.014 / 1K Tokens | 支持 | 2023年11月6日更新的模型|
| gpt-3.5-turbo-0125 | 0.0035 / 1K Tokens | 0.0105 / 1K Tokens | 支持 | 2024年1月25日最新模型，数据最新，价格更更低，速度更快，修复了一些1106的bug。|
| gpt-3.5-turbo-16k | 0.021 / 1K Tokens | 0.028 / 1K Tokens | 支持 | 适合快速回答简单问题,字数更多 |
| gpt-3.5-turbo-instruct | 0.0105 / 1K Tokens | 0.014 / 1K Tokens | 支持 |Completions模型 用于文本生成，提供准确的自然语言处理模型一般人用不上|
| gpt-4.5-preview | 0.525 / 1K Tokens | 1.05 / 1K Tokens | 支持 | openai最新模型，gpt-4.5 |
| gpt-4.5-preview-2025-02-27  | 0.525 / 1K Tokens | 1.05 / 1K Tokens | 支持 | openai最新模型，gpt-4.5 |
| o1-mini | 0.021 / 1K Tokens | 0.084 / 1K Tokens | 支持 | 针对复杂任务的推理模型 |
| o1-preview | 0.105 / 1K Tokens | 0.42 / 1K Tokens | 支持 | 针对复杂任务的推理模型 |
| o3-mini [5]| 0.0088 / 1K Tokens | 0.0352 / 1K Tokens | 支持 | 针对复杂任务的推理模型 |
| o1 [5]| 0.12 / 1K Tokens | 0.48 / 1K Tokens | 支持 | 针对复杂任务的推理模型,迄今为止最牛的模型 |
| gpt-4o-search-preview  | 0.02125/1K Tokens | 0.085/1K Tokens| 支持 | Openai 出的搜索模型,支持网络搜索,指向最新的4o的搜索模型|
| gpt-4o-search-preview-2025-03-11| 0.02125/1K Tokens | 0.085/1K Tokens| 支持 | Openai 出的搜索模型,支持网络搜索|
| gpt-4o-mini-search-preview | 0.001275/1K Tokens | 0.0051 /1K Tokens| 支持 | Openai 出的搜索模型,支持网络搜索,指向最新的4o-mini的搜索模型|
| gpt-4o-mini-search-preview-2025-03-11 |  0.001275/1K Tokens | 0.0051 /1K Tokens| 支持 | Openai 出的搜索模型,支持网络搜索|
| gpt-4 | 0.21 / 1K Tokens | 0.42 / 1K Tokens | 支持 | 默认模型，等于gpt-4-0613 |
| gpt-4o | 0.0175/1K Tokens + 图片费用[2]| 0.07/1K Tokens| 支持 | Openai 价格更低, 速度更快更聪明,指向最新版的4o版本|
| gpt-4o-2024-05-13 | 0.035/1K Tokens + 图片费用[2]| 0.105/1K Tokens | 支持 | Openai 2024-05-13出的gpt-4o模型|
| gpt-4o-2024-08-06 | 0.0175/1K Tokens + 图片费用[2]| 0.07/1K Tokens | 支持 | Openai 2024-08-06出的gpt-4o模型 支持128k输入,16k输出|
| gpt-4o-2024-11-20 | 0.0175/1K Tokens + 图片费用[2]| 0.07/1K Tokens | 支持 | Openai 2024-11-20出的gpt-4o模型, 该模型的创意写作能力得到了提升一更自然、更有吸引力、更有针对性的写作|
| chatgpt-4o-latest | 0.035/1K Tokens + 图片费用[2]| 0.105/1K Tokens | 支持 | 动态更新的版本，持续集成OpenAI最新的研究成果[4]|
| gpt-4o-mini | 0.00105/1K Tokens + 图片费用[2]| 0.0042/1K Tokens| 支持 | Openai 最新模型, 价格更低, 输出质量在3.5之上4o之下, 并且支持读图|
| gpt-4-0613 | 0.21 / 1K Tokens | 0.42 / 1K Tokens | 支持 | 2023年6月13日更新的模型 |
| gpt-4-turbo-preview | 0.07 / 1K Tokens| 0.21 / 1K Tokens | 支持 | 最新模型，输入128K，输出最大4K，知识库最新2023年4月, 此模型始终指向最新的4的preview模型|
| gpt-4-0125-preview | 0.07 / 1K Tokens| 0.21 / 1K Tokens | 支持 | 2024年1月25日更新的模型，输入128K，输出最大4K，知识库最新2023年4月, 修复了一些1106的bug|
| gpt-4-1106-preview | 0.07 / 1K Tokens| 0.21 / 1K Tokens | 支持 | 2023年11月6日更新的模型，输入128K，输出最大4K，知识库最新2023年4月|
| gpt-4-vision-preview | 0.07 / 1K Tokens + 图片费用[2]| 0.21 / 1K Tokens | 支持 |多模态，支持图片识别|
| gpt-4-turbo | 0.07 / 1K Tokens + 图片费用[2]| 0.21 / 1K Tokens | 支持 | Openai 最新模型多模态，支持图片识别，支持函数tools|
| gpt-4-turbo-2024-04-09 | 0.07 / 1K Tokens + 0.10115\*图片个数[2]| 0.21 / 1K Tokens | 支持 | Openai 最新模型多模态，支持图片识别，支持函数tools|
| gpt-3.5-turbo-ca | 0.001 / 1K Tokens | 0.003 / 1K Tokens | 支持 | Azure openai中转(也属于官方模型的一种)价格便宜, 但是回复的慢一些|
| gpt-4-ca | 0.12 / 1K Tokens | 0.24 / 1K Tokens | 支持 |第三方优质提供商提供的服务,优点价格便宜,但是稳定性没有非-ca的好, 模型返回和能力都是一样的|
| gpt-4-turbo-ca | 0.04 / 1K Tokens + 0.0578\*图片个数[3]| 0.12 / 1K Tokens | 支持 |第三方优质提供商提供的服务,优点价格便宜,但是稳定性没有非-ca的好, 模型返回和能力都是一样的|
| gpt-4o-ca | 0.01 / 1K Tokens + 0.0289\*图片个数[3]| 0.04 / 1K Tokens | 支持 | 第三方优质提供商提供的服务,优点价格便宜,但是稳定性没有非-ca的好, 模型返回和能力都是一样的|
| gpt-4o-mini-ca | 0.00075 / 1K Tokens| 0.003 / 1K Tokens | 支持 | 第三方优质提供商提供的服务,优点价格便宜,但是稳定性没有非-ca的好, 模型返回和能力都是一样的|
| chatgpt-4o-latest-ca | 0.02 / 1K Tokens| 0.06 / 1K Tokens | 支持 | 第三方优质提供商提供的服务,优点价格便宜,但是稳定性没有非-ca的好, 模型返回和能力都是一样的|
| o1-mini-ca | 0.012 / 1K Tokens | 0.048 / 1K Tokens | 支持 | 第三方优质提供商提供的服务,优点价格便宜,但是稳定性没有非-ca的好, 模型返回和能力都是一样的 |
| o1-preview-ca | 0.06 / 1K Tokens | 0.24 / 1K Tokens | 支持 | 第三方优质提供商提供的服务,优点价格便宜,但是稳定性没有非-ca的好, 模型返回和能力都是一样的 |
| deepseek-reasoner | 0.0036  / 1K Tokens | 0.0144 / 1K Tokens | 支持 |deepseek的思考R1模型, 此模型由第三方供应商自己部署提供，有小概率可能会出现响应速度较慢或报错的情况。|
| deepseek-r1 | 0.0024  / 1K Tokens | 0.0096 / 1K Tokens | 支持 |deepseek的思考R1模型, 此模型由第三方(火山引擎)供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| deepseek-v3 | 0.0012  / 1K Tokens | 0.0048 / 1K Tokens | 支持 |deepseek的聊天模型, 此模型由第三方(火山引擎)供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| claude-3-7-sonnet-20250219 | 0.015 / 1K Tokens | 0.075 / 1K Tokens | 支持 |claude的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| claude-3-5-sonnet-20240620 | 0.015 / 1K Tokens | 0.075 / 1K Tokens | 支持 |claude的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| claude-3-5-sonnet-20241022 | 0.015 / 1K Tokens | 0.075 / 1K Tokens | 支持 |claude的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| claude-3-5-haiku-20241022 | 0.005 / 1K Tokens | 0.025 / 1K Tokens | 支持 |claude的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-1.5-flash-latest | 0.0006 / 1K Tokens | 0.0024 / 1K Tokens | 支持 |Google Gemini 的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-1.5-pro-latest | 0.01 / 1K Tokens | 0.04 / 1K Tokens | 支持 |Google Gemini 的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-exp-1206 | 0.01 / 1K Tokens | 0.04 / 1K Tokens | 支持 |Google Gemini 的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-2.0-flash-exp | 0.01 / 1K Tokens | 0.04 / 1K Tokens | 支持 |Google Gemini 的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-2.0-pro-exp-02-05 | 0.01 / 1K Tokens | 0.04 / 1K Tokens | 支持 |Google Gemini 的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-2.0-flash | 0.005 / 1K Tokens | 0.02 / 1K Tokens | 支持 |Google Gemini 的模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-2.5-pro-exp-03-25 | 0.01 / 1K Tokens | 0.04 / 1K Tokens | 支持 | 是gemini 最新的旗舰模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-2.5-pro-preview-05-06 | 0.01 / 1K Tokens | 0.04 / 1K Tokens | 支持 | 是gemini 最新的旗舰模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| gemini-2.5-flash-preview-04-17 | 0.0006 / 1K Tokens | 0.014 / 1K Tokens | 支持 | 是gemini 最新的旗舰模型, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| grok-3 | 0.016 / 1K Tokens | 0.08 / 1K Tokens | 支持 |grok基础模型（网页逆向版）, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| grok-3-reasoner | 0.016 / 1K Tokens | 0.08 / 1K Tokens | 支持 |推理增强模型（网页逆向版）, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|
| grok-3-deepsearch | 0.016 / 1K Tokens | 0.08 / 1K Tokens | 支持 |深度联网搜索模型（网页逆向版）, 此模型由第三方供应商提供，有小概率可能会出现响应速度较慢或报错的情况。|

| **模型（Model）** | **价格** | **是否支持** |
| --- | --- | --- |
| gpt-image-1 | 文字输入: 0.04CA/1K Tokens, 图片输入: 0.08CA/1K Tokens, 图片输入：0.32 CA/1K Tokens | 支持 |
| dall-e-3 1024×1024 | 0.280 / image | 支持 |
| dall-e-3 1024×1792 | 0.560 / image | 支持 |
| dall-e-3-hd 1024×1024 | 0.560 / image | 支持 |
| dall-e-3-hd 1024×1792 | 0.840 / image | 支持 |
| dall-e-2 1024×1024 | 0.14 / image | 支持 |
| dall-e-2 512x512 | 0.126 / image | 支持 |
| dall-e-2 256x256 | 0.112 / image | 支持 |
| tts-1 | 0.105 / 1K characters | 支持 |
| tts-1-hd | 0.21 / 1K characters | 支持 |
| gpt-4o-mini-tts | (0.12 / minute) + (0.012 / 1kToken) | 支持 |
| Whisper | 0.042 / minute | 支持 |
| gpt-4o-mini-transcribe | 0.024 / minute | 支持 |
| gpt-4o-transcribe | 0.048 / minute | 支持 |
| text-embedding-ada-002 | 0.0007 / 1K Tokens | 支持 |
| text-embedding-3-small | 0.00014 / 1K Tokens | 支持 |
| text-embedding-3-large | 0.00091 / 1K Tokens | 支持 |

[1] Tokens: GPT中指文本数据的最小处理单位。一个token可以是一个字、一个词或者一个字符，这取决于所使用的语言和处理方式。例如，在英文中，一个token可能是一个单词，如"apple"；在中文中，一个token可能是一个字符，如"苹"。 1K Tokens = 1000个Token。（根据经验估算：gpt-4o模型 1000Tokens≈1000-1200个中文字符；非gpt-4o模型1000Tokens≈700-800中文字符）

[2] 多模态模型图片如何计算占用tokens请参考OpenAI官方 https://openai.com/api/pricing 。分辨率越高，tokens占用越多，但最高不会超过1445tokens。

[3] CA系列多模态模型在计算图片价格时，如果使用流式传输(参数stream=true)，则按照0.10115每张图计费；如果使用非流式传输（参数stream=false），这时按照OpenAI返回的实际消耗量计费，如果你的图片分辨率较低，通常低于0.10115。因此，我们建议在使用gpt-4-turbo分析图片时，使用非流式传输（参数stream=false）。

[4] 动态更新的版本，持续集成OpenAI最新的研究成果。它为开发人员和研究人员提供了探索最前沿技术的机会。请注意，尽管该模型展示了最新的能力，但对于生产环境的使用，我们仍然建议选择经过优化的旧版GPT模型，以确保更高的稳定性和性能

[5] o1和o3-mini由于这两种模型的可用账号数量较少，资源稳定性可能存在波动，即可能出现时可用、时不可用的情况。建议如在生产环境中使用时做好相应的容错处理。

## 如何使用
- 由于频繁的恶意请求，我们不再直接提供公共的免费Key，现在需要你使用你的Github账号绑定来领取你自己的免费Key。
- 🚀[申请领取内测免费API Key](https://api.chatanywhere.org/v1/oauth/free/render) 或 [购买内测付费API Key](https://api.rcouyi.com/register?aff=5kMw)
- 测试区服务转发Host1: `https://api.chatanywhere.tech` (国内中转，延时更低)
- 测试区服务转发Host2: `https://api.chatanywhere.org` (国外使用)
- 余额和使用记录查询（通知公告也会发在这里）: [余额查询及公告](https://api.chatanywhere.tech/)
- 测试区服务和付费版服务分中转Host服务器不同，具体请自行前往[付费key购买页面](https://api.rcouyi.com/register?aff=5kMw)
