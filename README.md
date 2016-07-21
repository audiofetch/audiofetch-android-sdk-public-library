# AudioFetch Android SDK Library

This is the AudioFetch SDK Library for public consumption.

To include and use the library:

1.  Copy the libs/afaudiolib.aar to your projects libs folder.
2.  Add the following snippet to your repositories section of the app's build.gradle

```
repositories {
    mavenCentral()
    flatDir {
        dirs 'libs'
    }
}
```

3.  Add the following to the dependencies section of the app's build.gradle

```
dependencies {
    compile 'com.android.support:support-v4:23.+'
    compile 'com.android.support:appcompat-v7:23.+'
    compile 'com.android.support:support-v13:23.+'
    compile 'com.android.support:support-annotations:23.+'

    compile(name: 'afaudiolib', ext: 'aar')
    // required by above AudioFetch SDK
    compile 'com.squareup:otto:1.3.8'
    compile 'com.google.guava:guava:19.0'
}
```

See documentation and reference architecture app for more implementation details.
