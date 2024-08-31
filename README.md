# EasyJavascript2
이 저장소는 누구나 쉽게 쓴 자바스크립트 책을 학습한 내용입니다.

아래 오류 발생 했을 때

% git push origin main

remote: Permission to kimsijin33/EasyJavascript2.git denied to youngPerson1999.

fatal: unable to access 'https://github.com/kimsijin33/EasyJavascript2.git/': The requested URL returned error: 403


해결 방법

저장소 주소을 아래와 같이 변경

% git remote set-url origin https://KimSiJin@github.com/kimsijin33/EasyJavascript2.git

% git remote -v

origin	https://KimSiJin@github.com/kimsijin33/EasyJavascript2.git (fetch)

origin	https://KimSiJin@github.com/kimsijin33/EasyJavascript2.git (push)

그다음 push 하면 잘된다!


