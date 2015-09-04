Picasso
=======

A powerful image downloading and caching library for Android with Base64 support.

![](website/static/sample.png)

For more information please see [the website][1]



Download
--------

* Download [the latest AAR from releases][2].
* Place the AAR in your application's `Library folder` (usually 'libs').
* Add the following lines to your application's `build.gradle` file:

```Groovy
repositories {
    flatDir {
        dirs 'libs'
    }
}

dependencies {
    compile(name:'picassobase64-release', ext:'aar')
}
```

ProGuard
--------

If you are using ProGuard you might need to add the following option:
```
-dontwarn com.squareup.okhttp.**
```



License
--------

    Copyright 2013 Square, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


 [1]: http://square.github.io/picasso/
 [2]: https://github.com/chRyNaN/PicassoBase64/releases/download/v1.0.0/picassobase64-release.aar
