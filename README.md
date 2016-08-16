# NIM iOS SDK Lite
[网易云信](http://netease.im)是由网易发布的一款 IM 云服务产品。此仓库是云信 iOS SDK 精简版本的发布仓库。

## 使用方法
* 通过  [release](https://github.com/netease-im/NIM_iOS_SDK/releases) 下载相应 SDK 包

* 使用 'pod NIMSDK_LITE'。

## 差异
和官网版本提供完整的静态包不同，这仓库中的 NIM SDK 是以 “主静态库 + 依赖的第三方静态库” 的形式提供，形式不同，并去掉了音视频模块，如果不需要使用实时音视频能力的用户推荐使用此版本。

