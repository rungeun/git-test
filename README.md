# git-test
git test.


# 이전에 정리해 두었던 내용
~/Desktop/Development/

pwd 현재 위치 경로 보기
ls -al 상세 정보 포함 디렉터리 보기

git init 초기화

git status 깃 상태 확인

git add " " 스테이징(최초 추적시, 파일 수정시) (커밋 대기 상태)
git add . 작업트리에서 수정한 모든 파일을 스테이징

git commit -m "message" 커밋, 메시지 등록

git log 버전 확인
git log -p 바뀐 내용 확인(커밋후)

git diff 수정 사항 보기(커밋전)
diff --git a/f1.txt b/f1.txt
index b323a15..9462317 100644
--- a/f1.txt    변경전 버전
+++ b/f1.txt 변경후 버전
@@ -1 +1 @@
-SOUCE : 2
+f1.txt : 2

git commit -am 스테이징-커밋 한번에
스테이지 - 커밋 - 레파지토리

git branch " " 브랜치 만들기 (분기)

git checkout " " 브렌치 전환

git log --branches --decorate --graph 브렌치 상황 보기
git log --branches --decorate --graph --oneline 간결하게 브렌치 상황 보기


! README파일은 MAIN브렌치에서 커밋
! 그 외는 그 외 브렌치에서 처리


hotfix_ 실서버에서 문제가 생겼을 때 급하게 작업하기 위한 브랜치
feature_ 이슈 수정 및 추가 개발에 사용되며 실제로는 푸쉬하지 않을 브랜치
release_ 실서버에 푸쉬하면서 최종적으로 이슈를 해결할 브랜치
branch 이름
Exp_ 기능개발
Iss_  이슈