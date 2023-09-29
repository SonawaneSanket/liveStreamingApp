# flutter-live

![](https://ossrs.net/gif/v1/sls.gif?site=github.com&path=/srs/flutter_live)
[![Pub Version](https://img.shields.io/pub/v/flutter_live)](https://pub.dev/packages/flutter_live)
[![](https://cloud.githubusercontent.com/assets/2777660/22814959/c51cbe72-ef92-11e6-81cc-32b657b285d5.png)](https://github.com/ossrs/srs/wiki/v1_CN_Contact#wechat)

cross-platform(iOS+Andriod)multi-protocol(RTMP/HTTP-FLV/HLS/WebRTC)live streaming App, Flutter+[SRS](https://github.com/ossrs/srs)。

Live Streaming player, iOS+Android, RTMP/HTTP-FLV/HLS/WebRTC, by Flutter+[SRS](https://github.com/ossrs/srs).

## Usage

Set up a proxy in the country:
```bash
export FLUTTER_STORAGE_BASE_URL=https://storage.flutter-io.cn && 
export PUB_HOSTED_URL=https://pub.flutter-io.cn
```

Compile and run SRS live streaming (iOS can be installed from https://ossrs.netre)：

```
git clone https://github.com/ossrs/flutter_live.git &&
cd flutter_live/example && flutter run
```

> Warning: Not support iOS simulator, [#14647](https://github.com/flutter/flutter/issues/14647).

![Home](https://ossrs.net/srs.release/images/01-home-02.jpg)

![Home](https://ossrs.net/srs.release/images/02-show-01.jpg)

![Home](https://ossrs.net/srs.release/images/03-realtime.jpg)

