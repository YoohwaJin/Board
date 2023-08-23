# 오늘 수업 기록할 것

- 프로젝트 생성 / 앱 생성
```bash
django-admin startproject <pjt_name>
djanfo-admin startapp <app_name>
```

- 그 나머지
```bash
python manage.py <command>
```

# http status code
- 200: 잘 되고 있음
- 30x: redirect

- 4xx: client error
    - 401: Unauthorized
    - 403: Forbidden
    - 404: not found (주소 입력 잘못함)

- 500: server error