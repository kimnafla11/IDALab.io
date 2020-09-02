<p align = 'center'>
   <img src="https://koptimizer.github.io/IDALab.io/assets/img/IDAL_gray_1.png" width="500" height="500"><br>
   <b>www.idalab.ac.kr</b>
</p>

### IDAL 홈페이지 관리 핵심파일
- ```_config.yml```을 통해서 홈페이지 Title과 description, 메인 화면 텍스트를 변경할 수 있습니다.
- ```_includes```의 html 파일을 통해서 홈페이지 내부의 모든 내용을 변경할 수 있습니다.
- ```assets/css/main.css```를 통해서 대부분의 속성들을 정의해줄 수 있습니다.
- 모든 이미지는 ```_assets/img```에 저장해서 사용해주세요.

### 온라인에서 작업하는 방법
- Github이나 Github Desktop을 이용해서 해당 파일에 접근한 후 수정해서 commit을 해주시면 바로 적용이 됩니다.
- 실제 웹으로 적용되기까지 1~30분 가량의 시간이 걸리나 수정이 간편해서 간소한 수정에 용이합니다.

### 로컬PC에서 작업하는 방법
- Ruby와 Jekyll을 다운받아 설치합니다.
- ```$ git clone``` 혹은 ```$ git pull```을 통해 해당 레포지토리를 끌어옵니다.
- Ruby prompt를 켜고 로컬에 저장된 레포지토리로 이동한 후, ```jykell serve```를 입력합니다.
- serve를 실행하면 localhost:4000에서 자신이 작업하는 홈페이지의 모습을 바로 확인할 수 있습니다.
- 수정이 완료되었다면 ```$ git pull```후, add -> commit -> push (-> pull reqeust)를 해주시면 됩니다.

### 주의점
- 중요한 정보는 홈페이지에 연동 및 업로드 하지 말아주세요. (보안이 취약합니다.)
