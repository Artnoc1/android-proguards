# android proguards

[![Android Weekly](https://img.shields.io/badge/Android%20Weekly-%23230-blue.svg)](http://androidweekly.net/issues/issue-230)
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-android--proguards-brightgreen.svg?style=flat)](http://android-arsenal.com/details/1/4600)
[![JitPack](https://img.shields.io/github/tag/yongjhih/android-proguards.svg?label=JitPack)](https://jitpack.io/#yongjhih/android-proguards)
[![Build Status](https://travis-ci.org/yongjhih/android-proguards.svg)](https://travis-ci.org/yongjhih/android-proguards)

[![proguard-snippets.png](art/proguard-snippets.png)](art/proguard-snippets.png)

Use one line to apply almost famous libraries of proguard configurations:

```gradle
compile 'com.infstory:proguard-snippets:1.0.0'
```

That's it.

## Installation

Via jcenter

```gradle
repositories {
    jcenter()
}

dependencies {
    compile 'com.infstory:proguard-snippets:1.0.0'
}
```

Or via jitpack.io

```gradle
repositories {
    jcenter()
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'com.github.yongjhih.android-proguards:android-proguards:-SNAPSHOT'
}
```

Specify RxJava proguard rules:

```gradle
repositories {
    jcenter()
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'io.reactivex:rxjava:1.2.1'
    compile 'com.github.yongjhih.android-proguards:rxjava-pro:-SNAPSHOT'
}
```

For each proguard rule dep:

```gradle
compile 'com.github.yongjhih.android-proguards:acra-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:action-bar-sherlock-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:activeandroid-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:adjust-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:admob-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:alibaba-fastjson-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:androidannotations-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:android-gif-drawable-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:androidquery-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:android-view-animations-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:auto-parse-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:avro-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:aws-1.7-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:aws-2.1.5-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:butterknife-6-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:butterknife-7-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:calligraphy-2.1.0-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:circular-progress-button-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:crashlytics-1-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:crashlytics-2-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:crittercism-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:crosswalk-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:dagger-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:deeplinkdispatch-1.5-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:easy-adapter-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:eventbus-2-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:eventbus-3-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:fabric-twitter-kit-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:facebook-conceal-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:facebook-fresco-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:facebook-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:facebook-stetho-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:flurry-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:glide-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:google-admob-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:google-analytics-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:google-auto-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:google-iap-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:google-play-services-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:greendao-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:gson-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:guava-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:icepick-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:jackson-2-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:joda-convert-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:joda-time-android-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:joda-time-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:jsoup-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:logansquare-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:logback-android-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:mikepenz-android-iconics-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:mixpanel-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:mopub-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:mpandroidchart-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:new-relic-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:okhttp3-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:okhttp-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:okio-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:otto-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:parceler-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:parse-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:picasso-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:project-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:realm-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:retrofit2-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:retrofit-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:retrolambda-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:rxjava-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:rxjava-promises-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:signpost-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:simple-parse-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:simple-xml-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:sqlite-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:support-design-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:support-v7-appcompat-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:support-v7-cardview-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:svgandroid-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:tencent-bugly-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:twowayview-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:wire-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:wizardroid-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:google-gms-safetynet-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:google-gms-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:zendesk-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:zendesk-chat-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:auto-bundle-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:webkit-pro:-SNAPSHOT'
compile 'com.github.yongjhih.android-proguards:apache-http-legacy-pro:-SNAPSHOT'
```

## Details

Pack proguard rules as `proguard.txt` into AAR with [`consumerProguardFiles`](https://github.com/yongjhih/android-proguards/blob/master/rxjava-pro/build.gradle#L26) android-gradle ([0.5.7+](http://tools.android.com/tech-docs/new-build-system)) directive.

```sh
wget https://bintray.com/yongjhih/maven/download_file?file_path=com%2Finfstory%2Fproguard-snippets%2F1.0.0%2Fproguard-snippets-1.0.0.aar
mv proguard-snippets-1.0.0.aar a.zip
unzip a.zip
```

You can find out `proguard.txt`.

## See Also

* [krschultz/android-proguard-snippets](https://github.com/krschultz/android-proguard-snippets)

## Libraries

* [ACRA 4.5.0](https://github.com/ACRA/acra)
* [ActionBarSherlock 4.4.0](http://actionbarsherlock.com/)
* [ActiveAndroid](http://www.activeandroid.com/)
* [Adjust](https://github.com/adjust/android_sdk)
* [Amazon Web Services 1.6.x / 1.7.x](https://aws.amazon.com/releasenotes/Android/1855915734308772)
* [Amazon Web Services 2.1.x](https://github.com/aws/aws-sdk-android)
* [AndroidAnnotations](http://androidannotations.org/)
* [android-gif-drawable](https://github.com/koral--/android-gif-drawable)
* [Apache Avro](http://http://avro.apache.org/)
* [Alibaba Fastjson](https://github.com/alibaba/fastjson)
* [Butterknife 5.1.2](http://jakewharton.github.io/butterknife/)
* [Crashlytics 1.+ / 2.+](http://try.crashlytics.com/sdk-android/)
* [Crittercism](http://docs.crittercism.com/android/android.html)
* [EventBus 2.0.2](https://github.com/greenrobot/EventBus)
* [Facebook 3.2.0](https://developers.facebook.com/docs/android/)
* [Facebook Conceal](https://facebook.github.io/conceal/)
* [Facebook Stetho](https://facebook.github.io/stetho/)
* [Facebook Fresco](https://github.com/facebook/fresco)
* [Flurry 3.4.0](http://support.flurry.com/index.php?title=Analytics/Code/ReleaseNotes/Android)
* [Google Analytics 3.0+](https://developers.google.com/analytics/devguides/collection/android/v3/)
* [Google Guava](https://code.google.com/p/guava-libraries/)
* [Google Play Services 4.3.23](http://developer.android.com/google/play-services/setup.html)
* [GreenDao 1.3.x](http://greendao-orm.com/)
* [GSON 2.2.4](https://code.google.com/p/google-gson/)
* [Jackson 2.x](http://wiki.fasterxml.com/JacksonHome)
* [Joda-Convert 1.6](http://www.joda.org/joda-convert/)
* [Joda-Time 2.3](http://www.joda.org/joda-time/)
* [Jsoup](http://jsoup.org/)
* [LoganSquare](https://github.com/bluelinelabs/LoganSquare)
* [New Relic](https://docs.newrelic.com/docs/mobile-monitoring/mobile-sdk-api/new-relic-mobile-sdk-api/working-android-sdk-api)
* [Parse](https://parse.com/products/android)
* [Realm](http://realm.io/news/realm-for-android/)
* [RxJava 0.21](https://github.com/ReactiveX/RxJava/wiki/The-RxJava-Android-Module): RxJava2+ no need anymore
* [RxJava-Promises](https://github.com/darylteo/rxjava-promises)
* [Support Library v7](https://developer.android.com/tools/support-library/features.html#v7-appcompat): 23+ should already consumed
* [Sqlite](http://www.sqlite.org/index.html)
* [Square Dagger](https://github.com/square/dagger)
* [Square OkHttp](http://square.github.io/okhttp/)
* [Square Okio](https://github.com/square/okio)
* [Square Otto](http://square.github.io/otto/)
* [Square Picasso](https://github.com/square/picasso)
* [Square Retrofit](http://square.github.io/retrofit/): Retrofit1 and Retrofit2
* [Square Wire](https://github.com/square/wire)
* [Square LeakCanary](https://github.com/square/leakcanary) 1.4+ already consumed
* [SVG Android](https://github.com/pents90/svg-android)
* [Icepick](https://github.com/frankiesardo/icepick)
* [Simple-Xml](http://simple.sourceforge.net/)
* [Tencent Bugly](http://bugly.qq.com/)

## Credit

* Krschultz: [krschultz/android-proguard-snippets](https://github.com/krschultz/android-proguard-snippets)

## License

```
Copyright 2015 8tory, Inc.
Copyright 2013 Kevin Schultz

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

