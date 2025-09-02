cd <설치할 프로젝트 폴더 경로. 전역으로 설치 안하고 지역으로.. 글로벌 xx> 
<br/>
python -m venv .venv 가상환경 설치(.venv는 일반적으로 사용되는 디렉토리 이름)
<br/>
pip install flask 설치하기
**flask run 방법**
flask run 하면 활성화


python app.py 
종료는 ctrl + c 
<br/>
**가상환경 활성화 시키는 방법** 
Windows: <가상환경_디렉토리_이름>\Scripts\activate 
<br/>
**가상환경 비활성화 시키는 방법** 
deactivate 명령어 사용시 환경 종료 
<br/>
설치할 패키지가 있다면 pip install <패키지 이름>

<br/>
환경변수 만들기 (api key 보안)


!! flask에서 templates 폴더명사용 자동으로 읽어오기 때문에
</br>
app.py 에서 불러올 때는 render_template 라고 사용 s 오타 주의
