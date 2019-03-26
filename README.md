# 隱私保護政策 及 使用條款

## 開發時編譯
```
gulp build
```

## 開發完成打包
```
gulp package
```

產 travis 用的 gcs.json.enc
```
$ docker run -v [gcs.json dir path]:/tmp  -it ruby:2.6 /bin/bash
# cd /tmp
# gem install travis
# travis encrypt-file -t [travis user token] -r hanlin-edu-tech/info-qa gcs.json
```