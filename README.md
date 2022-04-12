# github markdown css 파일


## jsdelivr 업로드 방법

git명령어에서 tag로 버전을 기록하셔서 깃허브에 업로드하셔야 합니다.

git 사용자 설정 필요한경우

```javascript
git config user.email "이메일"
git config user.name "사용자명"
```


git을 설치하셨다는 가정하에 Git bash기준으로 설명드립니다.

1. github 에 public 로 저장소 생성
2. 로컬 git 용 폴더 생성 및 git 초기화 ( git init )
3. 로컬 폴더 리모트 투가 ( git remote add origin https://github.com/사용자명/repo명.git )
4. 업로드할 파일 저장 및 커밋
5. git 버전 태그 달기 git tag v1.0
6. 리모트 푸쉬 git push origin master
7. 태그 푸쉬 git push origin master --tags


jsdelivr 파일 업로드 형식은 아래와 같다 

https://cdn.jsdelivr.net/gh/[사용자명]/[저장소명]@[태그명]/[깃 파일경로]


## vscode 설정

setting.json

```json
{
"markdown.styles": [
"https://cdn.jsdelivr.net/gh/inno76tink/static@github/github/style.css"
]

}
```






[원본 저장소](https://github.com/aliencube/markdownpad-github)
