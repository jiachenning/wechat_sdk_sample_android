# wechat_sdk_sample_android
The demo of wechat sdk which could run correctly.

The original sdk demo is [here](https://pay.weixin.qq.com/wiki/doc/api/app/app.php?chapter=11_1).

It is  eclipse's style and can not run. Now I fix it with gradle.

**Problems** got fixed

- app/src/main/res/drawable-hdpi/send_music_thumb_backup.png is not a vlid png, it's a jpeg
- namespace are wrong, com.tencent.mm.sdk rename to com.tencent.mm.opensdk
- demo source and sdk's api version is conflict, WXImageObject has field called imagePath not imageUrl
