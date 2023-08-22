# 230822 homework #

## 1. git 기본 설정 ##
### - 사용자 등록: git config --global user.name/git config --global user.email ###
### - 등록 확인: git config --list  ###

## 2. 로컬 저장소 생성 ##
### - git init ###
### - 끝에 (main)이 표시되면 로컬 저장소 생성 완료  ###

## 3. 명령어로 파일 생성 ##
### - touch 파일명.txt ###
### - 파일이 생성 되면 add와 commit으로 등록  ###
### - git add 파일명.txt -> git commit -m "기록설명"  ###
### - git add .: 폴더 안에 등록이 안 된 모든 파일을 한번에 추가 ###
### - git commit -am "기록설명": 한번 이상 등록한 파일을 한번에 등록 ###
### - git status: 파일의 상태를 확인  ###
### - git log/log --oneline: 이력을 확인/이력을 간략하게 보여줌 ###

## 4. branch 생성 및 삭제 ##
### - git branch 폴더명 ###
### - git branch --list: branch 리스트 확인  ###
### - 만들고 난 직후에는 main(어디에 있는지 *로 표시)  ###
### - git branch switch 폴더명: 생성된 branch로 이동 (git switch -: 바로 직전에 있던 곳으로 이동) ###
### - git merge 폴더명: main + branch 병합 ###
### - 병합 후 내용 추가해야 할 때, 해당 branch에서 수정 후 main에 업데이트 ###
### - git branch -d 폴더명: branch 삭제 ###

## 5. github-1 ##
### - 온라인 상에서 git을 사용하기 위해 연결해주는 사이트 ###
### - git readme add origin 본인 github URL: git에 주소 등록 ###
### - git push -u origin main: 온라인에 업로드 ###
### - git remote rm origin: gi에 등록된 URL 삭제 (오류시 지우고 다시 하면 됨) ###

## 6. github-2 ##
### - Markdown: 일반 텍스트 기반의 경량 마크업 언어 ###
### - fork: 복사해서 옮겨오는 것 ###
### - fork를 하려면 __기존 로컬에서 나와(cd ../)__새로운 폴더에 __다운로드(git clone URL)__ 해야 함 ###
### - 수정한 후에 commit으로 등록하고 __업로드(git push -u origin 해당 로컬 저장소) ###
