
#### 파일업로드
awless 명령어를 사용해서 s3에 파일 업로드 하는 방법은 아래와 같습니다.

```bash
$ awless create s3object bucket=lazypic file=./uploadfile.ext
```

#### Static Website on S3
- lazypic의 S3 Static Website주소는 http://dev.lazypic.org 입니다.
- 해당 S3에 Static web site를 업로드 하는 방법은 아래와 같습니다.

```bash
$ awless create s3object bucket=dev.lazypic.org file=./index.html
```
