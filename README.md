## AndroidX AutofitTextView
-------

### Quick start
-------
1. Implement by jetpack to your build.gradle as `dependency{}`
```actionscript
dependencies {
    ...
    implementatino ""
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