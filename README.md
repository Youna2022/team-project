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


## 📄 프로젝트 소개

학생부터 교직원, 교수, 관리자까지 대학교에 꼭 필요한 서비스를 제공하는 사이트입니다.

<br></br><br></br>

## ⏰ 개발기간
* 2022.10.30 ~ 2022.12.19

<br></br><br></br>

## 2. 👥 팀원 구성
### 👩‍ 학생페이지🎓
* **공현지** : 학적 조회 및 수정, 성적 조회, 강의 평가 입력 및 수정
* **손신효** :  수강신청 신청 및 관리, 장바구니 신청 및 관리, 학생 과제 업로드, 강의 목록 조회
* **이례영** : 교재 관리, 도서 구매

<br></br>

### 👩‍💼 교직원 
* **오태우** : 공지사항, 쪽지
* **최혜선** : 결재, 강의 관리, 학사 관리, 교직원 - 마이페이지
* **한창훈** : 근태 관리, 부서 관리, 주소록 관리, 강의 평가 조회

<br></br>

### 👨‍🏫 교수 
* **신동호** : 메인페이지, 회원 계정 관리, 과제 관리, 강의 계획서 관리, 휴/보강 신청
* **허유나** : 메인페이지, 강의 개설 관리, 성적 관리, 출석 관리, 교수 - 마이페이지

<br></br><br></br>



## 3. 개발환경
<img width="913" alt="image" src="https://user-images.githubusercontent.com/108061839/217717430-8b97d01a-a8b5-43fd-9d20-5bb2d6f02e03.png">


## 4. 시스템 프로세스
<img width="943" alt="image" src="https://user-images.githubusercontent.com/108061839/217717758-7a1a4814-d2a7-47c8-a651-1a8a77bf0a3d.png">

## 5. ERD
<img width="732" alt="image" src="https://user-images.githubusercontent.com/108061839/217718173-e61adcb7-7cb9-4dcc-96de-b8e1fe4c97eb.png">

### 메인테이블 & 강의서비스 ERD
<img width="718" alt="image" src="https://user-images.githubusercontent.com/108061839/217718461-41b0531d-13cf-4656-89db-0fe6b1331952.png">
<img width="936" alt="image" src="https://user-images.githubusercontent.com/108061839/217718333-59a4bb7d-214c-4545-bbed-b0aff96fbef6.png">



<br></br><br></br>

### 📌 주요기능
* [👨‍🏫 교수페이지  주요 기능](#-학생페이지-주요-기능)
<img width="632" alt="image" src="https://user-images.githubusercontent.com/108061839/217718524-b01b7052-5fd4-4e9d-83eb-1eb57b16bd92.png">
<img width="640" alt="image" src="https://user-images.githubusercontent.com/108061839/217718575-cbdc194d-7ecb-43ac-9ef4-592e93769905.png">
<details><summary>👨‍🏫 교수페이지 화면 및 설명 보기
</summary>





## 👨‍🏫 교수페이지  주요 기능

<br></br>

### 1. 강의 개설
* 신청 강의 리스트 조회 및 상세 조회
* 강의 개설 신청 등록 및 수정
* 강의 검색
* 강의 삭제 : 교직원 승인 전인 강의만 삭제 가능.
<img width="618" alt="image" src="https://user-images.githubusercontent.com/108061839/217718701-b8b9431f-994d-4c69-91cc-67700be3fe72.png">


<br></br>

### 2. 성적관리
* 개설된 강의 리스트 조회
* 강의 정보 조회
* 강의 학생 및 성적 리스트 조회
* 엑셀 다운로드 / 업로드 : Poi 라이브러리를 사용.
<br>강의 학생 리스트를 다운 받은 후 엑셀에서 성적을 입력 한 후 업로드를 하면 엑셀에 입력한 성적 데이터가 화면에 표시된다. 
<br> **기대 기능** : 엑셀을 통한 성적입력이 좀더 편할 유저 편리성을 고려한 기능.
* 등급 계산 : <br>
등급계산 버튼 클릭 시 입력한 성적을 통해 총점과 등급(상대평가), 재수강 여부, 
상태(해당 row 미입력 정보) 표시등을 처리한다.
* 임시저장 : 성적 데이터를 DB에 저장.
* 성적마감 : 
* 성적 분포 현황 조회 : <br>
DB를 거치기 전 script를 통해 한 화면 안에서 학생들의 성적 분포를 조회.<br>
F를 제외한 나머지 학생의 등급별 인원과 배정 비율을 조회 할수 있다.<br>
❗️ 이 기능을 통해 성적 분포를 보며 등급 구간에 있는 점수를 조정할 수 있다.
<img width="621" alt="image" src="https://user-images.githubusercontent.com/108061839/217718725-cb08f5b4-6470-4bb8-bae9-0baa8e501d2b.png">
<img width="538" alt="image" src="https://user-images.githubusercontent.com/108061839/217718743-6a6cbf32-2291-4abf-b60a-623d91a20403.png">
<img width="624" alt="image" src="https://user-images.githubusercontent.com/108061839/217718769-bc457bf6-506e-4cb9-b494-c09b6f5ead9a.png">


<br></br>

### 3. 전자 출석부
* 강의 별 학생 리스트 조회
* 학생 인적사항 조회 : 사진, 학번, 학년, 학과
* 리스트 엑셀 다운
   * POI라이브러리를 사용하여 조회한 데이터를 엑셀 파일로 변환하여 다운로드.
   * 해당 파일수정 후 인쇄하여 오프라인 출석부로 사용 할 수 있다.
<img width="645" alt="image" src="https://user-images.githubusercontent.com/108061839/217718601-0f8d9bf2-1b3b-4e26-80d8-11fe4304c9b2.png">
<img width="698" alt="image" src="https://user-images.githubusercontent.com/108061839/217718652-126d4893-807a-4f77-955f-cb26c9839ceb.png">



</details>



