
#### 파일업로드
awless 명령어를 사용해서 s3에 파일 업로드 하는 방법은 아래와 같습니다.

```bash
$ awless create s3object bucket=lazypic file=./uploadfile.ext
```

#### Static Website on S3
- lazypic의 S3 Static Website주소는 http://lazypic.org 입니다.
- 해당 S3에 Static web site를 업로드 하는 방법은 아래와 같습니다.

```bash
$ awless create s3object bucket=lazypic.org file=./index.html
```

- images 폴더가 존재할 때 해당폴더에 image.png파일을 생성하는 방법은 아래와 같습니다.
```bash
$ awless create s3object bucket=lazypic.org/images/ file=./image.png
```

#### 사용자
- 사용자 리스트보기
```
$ awless ls users
```

