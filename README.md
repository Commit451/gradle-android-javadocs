# DEPRECATED
Use https://github.com/vanniktech/gradle-maven-publish-plugin instead.

# gradle-android-javadocs
Helps setup the tasks needed to generate javadocs and sources for an Android library.
Derived from the [example](https://github.com/jitpack/android-example/blob/master/library/build.gradle) provided by the great guys at [Jitpack](https://jitpack.io)

# Usage
Add this line to the end of your library's `build.gradle` to get it producing Javadocs and Sources!
```java
dependencies {
    //Your dependencies (if you have any)
}

apply from: 'https://raw.githubusercontent.com/Commit451/gradle-android-javadocs/2.0.0/gradle-android-javadocs.gradle'
```

License
--------

    Copyright 2021 Commit 451

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
