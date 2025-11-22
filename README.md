<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>Git 명령어 정리</title>
</head>
<body>

    <h2>기본 설정</h2>
    <p>
        <code>git config --global user.name "your_name"</code> : 깃허브에서 내 이름<br>
        <code>git config --global user.email "your_email"</code> : 깃허브에서 내 이메일(잘못쓰면 다른사람 태그됨)<br>
        <code>git config --list</code> : 정보 확인
    </p>

    <hr>

    <h2>&lt;Github에 처음 코드 업로드하기&gt;</h2>
    
    <p><code>git init</code> : 초기화</p>

    <h3>1. 파일 더하기</h3>
    <p>
        <code>git add .</code> : 추가할 파일 더하기( 점은 모든파일 )<br>
        or<br>
        <code>git add abcd.py</code> : 파일이름
    </p>

    <p><code>git status</code> : 상태확인</p>

    <h3>2. 히스토리 만들기</h3>
    <p><code>git commit -m "first commit"</code> : 히스토리 만들기(저장)</p>

    <p>
        <code>git remote add origin https://github.com/dddGithub/firstproject.git</code> : 주소는 복붙<br>
        <code>git remote -v</code> : 잘 연결됬는지 확인 (선택사항)
    </p>

    <h3>3. 깃허브 올리기</h3>
    <p><code>git push origin main</code> : 깃허브 올리기 (main 은 브랜치 이름)</p>

    <hr>

    <h2>주요 코드</h2>
    <pre>
git add .                     : 추가할 파일 더하기

git commit -m "first commit"  : 히스토리 만들기

git push origin master        : 깃허브로 올리기
    </pre>

    <hr>

    <h2>팀프로젝트</h2>
    <p><code>get clone 주소 폴더이름</code> : Github에서 소스코드 다운로드</p>
    
    <p><code>git checkout -b 브렌치이름</code> : Github에서 내 브렌치(branch)만들기</p>

    <p>
        <b>[내 브렌치에 소스코드 업데이트하기]</b><br>
        <code>git add .</code><br>
        <code>git commit -m "first commit"</code><br>
        <code>git push origin 브렌치이름</code>
    </p>

    <p><code>git pull origin master</code> : 마스터 브렌치에 소스 가져오기(pull)</p>
    
    <p><code>git checkout 브렌치이름</code> : 브렌치끼리 이동하는 법</p>

</body>
</html>
