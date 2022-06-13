[깃실행]
$ git add .
$ git commit -m "무엇을 했나"
$ git push origin master

[uWSGI]
- Django, 웹 서버 직접 통신
- python 패키지
- uwsgi.service: BackGround 실행

[nginx]
- Django와 연결된 uwsgi 서버 & 웹 서버 nginx
- 사용자의 요청(request)을 받아서 적적할 response를 해줌
-  