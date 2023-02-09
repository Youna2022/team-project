# team-project
# Spring Boot-Project_ '중앙대학교'🎓 
<div>
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white">
<img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<br>

<img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
<img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jQuery&logoColor=white"> 
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
</div>
<br><img width="848" alt="중앙대학교_표지" src="https://user-images.githubusercontent.com/108061839/217217877-793c744a-1889-4d5f-bd04-e905a16f8f74.png">


>Spirng Boot  + JSP 파싱 **대학교 종합포탈시스템** 

<br></br><br></br>


# 1. 📄 프로젝트 소개

학생부터 교직원, 교수, 관리자까지 대학교에 꼭 필요한 서비스를 제공하는 사이트입니다.

### ⏰ 개발기간
* 2022.10.30 ~ 2022.12.19

<br></br><br></br>

# 2. 👥 팀원 구성
<img width="714" alt="image" src="https://user-images.githubusercontent.com/108061839/217720979-cac22f17-cd04-4cd0-96da-d340f7129f38.png">
<img width="713" alt="image" src="https://user-images.githubusercontent.com/108061839/217721176-db5d5862-5023-4c0b-a5d3-55a4b22c60b0.png">
<img width="522" alt="image" src="https://user-images.githubusercontent.com/108061839/217721219-e4e5b8f2-6b82-473e-a5d5-ee20baec7bf8.png">

<br></br><br></br>

# 3. 🛠 개발환경
<img width="913" alt="image" src="https://user-images.githubusercontent.com/108061839/217717430-8b97d01a-a8b5-43fd-9d20-5bb2d6f02e03.png">
<br></br><br></br>

# 4. 📝 시스템 프로세스
<img width="943" alt="image" src="https://user-images.githubusercontent.com/108061839/217717758-7a1a4814-d2a7-47c8-a651-1a8a77bf0a3d.png">
<br></br><br></br>

# 5. 🧰 ERD
<img width="732" alt="image" src="https://user-images.githubusercontent.com/108061839/217718173-e61adcb7-7cb9-4dcc-96de-b8e1fe4c97eb.png">
<br></br>

### 메인테이블
<img width="718" alt="image" src="https://user-images.githubusercontent.com/108061839/217718461-41b0531d-13cf-4656-89db-0fe6b1331952.png">
<br></br>

### 강의서비스 테이블
<img width="936" alt="image" src="https://user-images.githubusercontent.com/108061839/217718333-59a4bb7d-214c-4545-bbed-b0aff96fbef6.png">
<br></br><br></br>

# 6. 주요기능 _ 👨‍🏫 교수페이지

<img width="632" alt="image" src="https://user-images.githubusercontent.com/108061839/217718524-b01b7052-5fd4-4e9d-83eb-1eb57b16bd92.png">
<img width="640" alt="image" src="https://user-images.githubusercontent.com/108061839/217718575-cbdc194d-7ecb-43ac-9ef4-592e93769905.png">
<details><summary>👨‍🏫 페이지 화면 및 설명 보기
</summary>

<br></br>



## 👨‍🏫 교수페이지 주요 기능

<br></br>

### 1. 강의 개설
<img width="618" alt="image" src="https://user-images.githubusercontent.com/108061839/217718701-b8b9431f-994d-4c69-91cc-67700be3fe72.png"><br>
* 개설신청한 강의 리스트 조회
* 신청한 강의 검색 : 년도/학기, 이수구분, 강의명 
* 리스트에서 강의 클릭 시 개설강의 상세 정보에 정보 조회.
* 정보 조회된 상태에서 수정 후 ‘저장’ 클릭 시 업데이트.
* ‘삭제’  클릭 시 강의 삭제 (미승인된 강의만)
* ‘신규’  클릭 시 새로운 강의 신청.
* 상세정보 자동 입력 :  년도, 학기,
* 이수구분 교양  선택 시 전공, 대상 학년, 건물명 세팅
* 이수구분 전필, 전선 선택 시 교수의 전공으로 선택




<br></br>

### 2. 성적관리
<img width="621" alt="image" src="https://user-images.githubusercontent.com/108061839/217718725-cb08f5b4-6470-4bb8-bae9-0baa8e501d2b.png"><br>
* 개설 승인된 강의 리스트 조회
* 강의 클릭 시  강의 정보 조회, 강의 학생, 성적정보 조회
* 강의 학생 수 조회
* 등급 계산 클릭 후 임시저장.(DB 저장)
* 모든 성적 입력 시 성적 마감버튼
* 엑셀 업로드를 통해 엑셀에 입력한 성적을 화면에 표시.
<br></br>

<img width="538" alt="image" src="https://user-images.githubusercontent.com/108061839/217718743-6a6cbf32-2291-4abf-b60a-623d91a20403.png"><br>
* 엑셀 다운 파일
* 성적 입력전엔 점수 입력폼만,
* 입력데이터가 있을 시 총점, 등급 데이터 포함
<br></br>

<img width="624" alt="image" src="https://user-images.githubusercontent.com/108061839/217718769-bc457bf6-506e-4cb9-b494-c09b6f5ead9a.png"><br>
* ‘등급계산’ 클릭시 성적 값 체크
* 총점, 등급계산.
* 출석점수를 통한 재수강 표시(20점 이하) 
* 성적 등급 분포 현황 표 업데이트.
* 배정인원, 비정비율 표시
<br></br>

### 3. 전자 출석부
<img width="645" alt="image" src="https://user-images.githubusercontent.com/108061839/217718601-0f8d9bf2-1b3b-4e26-80d8-11fe4304c9b2.png"><br>
* 강의 별 학생 정보 조회
* 강의 정보 조회

<img width="698" alt="image" src="https://user-images.githubusercontent.com/108061839/217718652-126d4893-807a-4f77-955f-cb26c9839ceb.png"><br>
* 엑셀 다운로드 클릭 시 학생 리스트 + 출결 입력 폼 다운
   * POI라이브러리를 사용.
   * 엑셀 다운로드 클릭 시 학생 리스트 + 출석점수 입력 폼 다운
* 셀렉트바를 클릭하여 다른 강의로 바로 이동





</details>



