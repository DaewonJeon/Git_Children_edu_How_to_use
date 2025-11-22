git config --global user.name "your_name"   깃허브에서 내 이름

git config --global user.email "your_email"   깃허브에서 내 이메일(잘못쓰면 다른사람 태그됨)

git config --list	정보 확인
====================================================

<Github에 처음 코드 업로드하기>

			git init		초기화

1. git add .		추가할 파일 더하기( 점은 모든파일 )
    or
   git add abcd.py	파일이름

			git status		상태확인

2. git commit -m "first commit"	히스토리 만들기(저장)

			git remote add origin https://github.com/dddGithub/firstproject.git  주소는 복붙

			git remote -v	잘 연결됬는지 확인 (선택사항)

3. git push origin main   깃허브 올리기 (main 은 브랜치 이름)

====================================================
주요 코드
git add .  	추가할 파일 더하기

git commit -m "first commit"  히스토리 만들기

git push origin master 	  깃허브로 올리기

====================================================

팀프로젝트

get clone 주소 폴더이름		Github에서 소스코드 다운로드

git checkout -b 브렌치이름	Github에서 내 브렌치(branch)만들기

git add .
git commit -m "first commit"	내 브렌치에 소스코드 업데이트하기
git push origin 브렌치이름


git pull origin master		마스터 브렌치에 소스 가져오기(pull)

git checkout 브렌치이름		브렌치끼리 이동하는 법
