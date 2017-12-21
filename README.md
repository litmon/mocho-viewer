# mocho-viewer

## release build

put `app/signingConfigs/release.gradle` and set gradle file like below.

```
signingConfigs {
  release {
    storeFile file('release.keystore')
    password 'hoge'
    keyAlias 'fuga'
    keyPassword 'hogefuga'
  }  
}
```

