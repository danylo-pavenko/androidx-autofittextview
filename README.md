## AndroidX AutofitTextView
-------

###### Current version:
[![](https://jitpack.io/v/Daniil-Pavenko/androidx-autofittextview.svg)](https://jitpack.io/#Daniil-Pavenko/androidx-autofittextview)

### Quick start
-------
1. Implement by jetpack to your build.gradle as `dependency{}`
```actionscript
dependencies {
    ...
    implementation 'com.github.Daniil-Pavenko:androidx-autofittextview:<latest version>'
}

```

And add repositories to your root build.gradle file.
```actionscript
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```


2. Add view to xml.
```xml
<com.dansdev.library_autofittextview.AutofitTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:singleLine="true"
    android:maxLines="2"
    android:textSize="40sp"
    app:minTextSize="16sp"
    />
```