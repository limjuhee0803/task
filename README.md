# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성
-

# 임주희

### git에 대하여

git: 분산 버전 관리 시스템

git config --global user.name "limjuhee"=> 로컬에 이름 등록
git config --global user.email "limjuhee0803@naver.com"=> 로컬에 이메일 등록

git add . 사용 후 git commit -m "파일 설명" => 파일 추가 방법 (add후에 commit 사용 필수)

git log --oneline => 해당 라인 커밋 이력 확인

git log --oneline --graph --all => 더 자세하게 로그 확인 가능)

git status => 현재 상태 확인

git branchh dev => 브랜치 생성 

git branch -a => 브랜치 리스트 확인

git branch -d dev => 브랜치 삭제

git switch => 이동의 역할

+ 명령어에 git이 안붙는 것은 리눅스 명령어 ex)pwd, touch


### git hub

git hub: 온라인에서 사용가능

git push -u origin main => 로컬에서 작업한 것을 깃 허브로

git clone http~ => 온라인 파일을 로컬로 복사 시