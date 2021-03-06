---

copyright:
  years: 2016, 2018
lastupdated: "2018-01-09"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:pre: .pre}

# 预安装的包
{: #openwhisk_ecosystem}

在 {{site.data.keyword.openwhisk}} 中，通过包的目录，您能够轻松地借助多个有用的功能增强应用程序，以及访问生态系统中的外部服务。启用了 {{site.data.keyword.openwhisk_short}} 的外部服务的示例包括 Cloudant、Message Hub、Watson、The Weather Company、Slack、GitHub 等等。
{: shortdesc}

目录在 `/whisk.system` 和 `/watson-iot` 名称空间中作为包提供。有关更多信息，请参阅[浏览包](openwhisk_packages.html#browse-packages)。

## 目录包
{: notoc}

| 包| 描述
|
| --- | --- |
| [/whisk.system/alarms](./openwhisk_alarms.html)| 用于创建定期触发器的包|
| [/whisk.system/cloudant](./openwhisk_cloudant.html)| 用于使用 [Cloudant noSQL DB](https://console.ng.bluemix.net/docs/services/Cloudant/index.html) 服务的包|
| [/whisk.system/github](./openwhisk_github.html)| 用于创建 [GitHub](https://developer.github.com/) 的 Webhook 触发器的包|
| [/whisk.system/messaging](./openwhisk_messagehub.html)| 用于使用 [Message Hub](https://console.ng.bluemix.net/docs/services/MessageHub/index.html) 服务的包|
| [/whisk.system/pushnotifications](./openwhisk_pushnotifications.html)| 用于使用 [Push Notification](https://console.ng.bluemix.net/docs/services/mobilepush/index.html) 服务的包|
| [/whisk.system/slack](./openwhisk_slack.html)| 用于发布到 [Slack API](https://api.slack.com/) 的包|
| [/whisk.system/watson-translator](./openwhisk_watson_translator.html)| 用于[文本翻译和语言识别](https://www.ibm.com/watson/developercloud/language-translator.html)的包|
| [/whisk.system/watson-speechToText](./openwhisk_watson_speechtotext.html)| 用于将[语音转换为文本](https://www.ibm.com/watson/developercloud/speech-to-text.html)的包|
| [/whisk.system/watson-textToSpeech](./openwhisk_watson_texttospeech.html)| 用于将[文本转换为语音](https://www.ibm.com/watson/developercloud/text-to-speech.html)的包|
| [/watson-iot/iot-gateway](https://console.stage1.bluemix.net/docs/services/IoT/gateways/iotgw.html) | 用于使用 [Watson IoT Platform Gateway](https://console.stage1.bluemix.net/docs/services/IoT/index.html) 服务的包|
| [/whisk.system/weather](./openwhisk_weather.html)| 用于使用 [Weather Company Data](https://console.ng.bluemix.net/docs/services/Weather/index.html) 服务的包|
| [/whisk.system/websocket](./openwhisk_websocket.html)| 用于使用 [Web Socket](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) 服务器的包|
