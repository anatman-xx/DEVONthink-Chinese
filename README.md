<div align="center">
<a href="https://www.devontechnologies.com/download/products.html" target="_blank"><img src="https://img.shields.io/badge/&#127744;_DEVONthink-v2.10-blue.svg" align="left"></a>
<a href="https://github.com/aoaoho/DEVONthink-Chinese/releases" target="_blank"><img src="https://img.shields.io/badge/DEVONthink_Chinese-v2.10--0.1.0-red.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAANCAYAAAHTSQ6PAAAABGdBTUEAALGPC/xhBQAAAuxJREFUKBVVUk1sE0cU/mZ2Zu1d27Edk8RpEiAgojStmoDaIqFWQqIq9FIJJDhw4AZHkHLg0JMvOVVquNJbOVWRqt7gggSXlksqhV5wqIghTkhM/hyvd53d9cz0OSaIjLSz38y8n++97wHv15yZs1gJfelrX055/2y9W9y//2NmZpA9PT5lnKSD/efLP2U96+Eo/L0mXob+vhkr9Y9+/2262HcQzDoA9+fn5Q0nP8yeXBgxud0R2CyNcnkRfO+5AxOI94YGuOEUvr5TPPHVgSv7eeCL1Phnp2a1SlYKn2JMVvV3Wb813HhbQ3WlimC4uCn82hpLuK2bTo+L3HIGbNWFtgHDKY5FPOJoi5IobnsclukQE7ATDF67jVoc7mzotiaDXnaQ9+P/n7OzOb1c61Uj/fVr09Pb7N7JyUdH+8ee5aeka5WtsynROp/c9VB9tQQuJcrpTFbE1Y2Tn/+2fmn94jEM/JBE/DoBrTWYFNDtGFaiqbm0wJdvFWAPEVNiezg/9YMW7/BVO11GYYWjew0y7ph3XcidFWzGYHOOJLMgCG+343BdRet1rYwKQ85+hPvJRDY/zhypVtvx2oPN1SUK0e7G7u6sVCrxgYXy0cL1K43HV094v8Izv0wnZNF/neodfZOzV7YKzPcHpVbjOtLHolYw5Debw2EYNUTGXQpb8V8N7+0DdhdHMn02e3O6J5uXQwlYOy5S/QKZSQOzJhFXBIwgzBk0VRUELezs1uH7PlLSxruM81+zB2e4C2Z4JLfFhMHI73XkbzfgvSD1npPGeWpIQgK2BKePkdzM4uDUB8YJC8LC0p3iBGg2+R4Q/Gth8VweUtnIfxMjOWDg/52CzFJvD2vwcWs+YIENwmliTvQhNYmpEVWIzYqEzNCZd2e6o4ImJopxGnpSh9xsUsdiVDMUxC42VKD6FkzcstPQgw4zkjHVRDvcVDFfiYClUOtXvoorNKy1zTDwt5rBHqLQLir3SM6Oh+qcx/8DE/gqK8kQwdUAAAAASUVORK5CYII=" align="left"></a>
<a href="https://github.com/aoaoho/DEVONthink-Chinese/issues/new" target="_blank"><img src="https://img.shields.io/badge/Github-New_issue-2cbe4e.svg" align="right"></a>
<a href="https://t.me/DEVONthink" target="_blank"><img src="https://img.shields.io/badge/Telegram-DEVONthink-5682a3.svg" align="right"></a>
</div>

# DEVONthink 简体中文语言包
三个授权版本有轻微差异，请按需食用。
> DEVONthink Personal  
DEVONthink Pro  
DEVONthink Pro Office

## 食用方法
[下载语言包.zip文件](https://github.com/aoaoho/DEVONthink-Chinese/releases)，解压后将 `zh_CN.lproj` 目录拷贝到 `/Applications/DEVONthink*.app/Contents/Resources/` （在应用图标上点右键 --> 显示包内容）目录下，重新启动应用即可。

> 翻译说明：
> - 此语言包完全基于官方英文版（`English.lproj`）进行翻译；
> - 此语言包内全部资源文件翻译较为完整，但包括偏好设置在内的部分界面仍然存在英文，可能是这部分内容未放到资源文件内，但基本达到无障碍使用了；
> - 有些词汇或段落翻译时候没有上下文可参照，翻译会有偏差甚至歧义，我发现问题会持续修正。

> 如果你的 macOS 系统语言**不是**简体中文，但又想让 DEVONthink 的软件界面显示中文，那么你可能需要切换一下 DEVONthink 的默认语言，提供两种方式任选：
> - 使用第三方软件：[App Language Chooser](https://itunes.apple.com/us/app/app-language-chooser/id451732904) 或 [Language Switcher](http://www.tj-hd.co.uk/en-gb/languageswitcher/)
> - 使用终端命令行：[修改 macOS 应用的界面语言](https://sspai.com/post/44536)

## 更新记录
**2018-05-28**
- 随官网软件版本升级到 v2.10。

**2018-05-17**
- 修正因 Localizable.strings 文件的一处错误而导致的部分翻译未正常显示；
- 一些其他优化。

**2018-04-18**
- 增加了 Personal 和 Pro 版本的支持。

**2018-04-15**
- 当前日期翻译版本仅在 v2.9.17 版本下进行测试（理论上可用于大部分临近版本），可正常使用，若发现问题欢迎指正；
- 起初尝试使用 @Leeatmy 的 [DEVONthink Pro v2.8.7 中文化](https://github.com/Leeatmy/DEVONthink-Pro-Chinese "Leeatmy/DEVONthink Pro 2.8.7 中文化（汉化）")，但比较后发现和当前版本差异较大，遂仅作参考。请根据需要获取相应版本。

## 版权说明
- 本资源仅作学习和交流之用，请勿用于任何商业用途；
- 原程序版权归其[开发商](https://www.devontechnologies.com/ "DEVONtechnologies")所有，请在遵守其相关条款前提下使用本资源；
- 本人不承担您因使用本资源而产生的所有可能的后果与责任。
