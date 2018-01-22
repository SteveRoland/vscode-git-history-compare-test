# vscode 의 git history plugin 오류 테스트.

## 상태 (진행중)
https://github.com/DonJayamanne/gitHistoryVSCode/issues/197

## 증상
compare against previous version 실행 시 추가/삭제가 반대로 표시됨.

![error-screenshot](https://user-images.githubusercontent.com/5535960/35203047-7b309940-ff69-11e7-8cdd-eacbdea0d6b4.png)

## 절차
1. git: View History (git log)
2. click the latest commit.
3. click the file in the commit list
4. click the compare against previous version in command