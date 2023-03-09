# Django와 함께 사용하는 SQL 데이터베이스

이 프로젝트는 Django에서 SQL 데이터베이스를 사용하는 방법을 보여주는 샘플 프로젝트입니다. 이 프로젝트에서는 SQLite를 SQL 데이터베이스로 사용합니다.

## 요구사항

이 프로젝트를 실행하려면 다음이 시스템에 설치되어 있어야합니다:

Python 3.6 이상
Django 3.0 이상
설치

이 저장소를 로컬 머신에 복제합니다:

```bash
git clone https://github.com/dayhang/sql_db_django.git
```
프로젝트 디렉토리로 이동합니다:

```bash
cd sql_db_django
```
필요한 패키지를 설치합니다:

```
pip install -r requirements.txt
```

마이그레이션을 적용합니다:
```
python manage.py migrate
```
서버 실행

서버를 실행하려면 다음 명령을 실행합니다:

```
python manage.py runserver
```

그런 다음 브라우저를 열고 http://localhost:8000/ 입력합니다.

##사용법

이 프로젝트는 사용자가 데이터베이스에서 책을 볼 수 있고 추가할 수 있는 간단한 웹 애플리케이션을 제공합니다. 네비게이션 바에서 "Books" 링크를 클릭하여 책 목록에 액세스 할 수 있습니다.

새 책을 추가하려면 책 목록 페이지에서 "Add book" 버튼을 클릭하십시오. 책 정보를 입력하고 "Save"를 클릭하여 데이터베이스에 책을 추가합니다.

##라이선스

이 프로젝트는 MIT 라이선스에 따라 라이선스가 부여됩니다. 자세한 정보는 LICENSE 파일을 참조하십시오.
