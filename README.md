# 2차 프로젝트 37-2nd-HAPPIN
<img src="https://user-images.githubusercontent.com/67556491/196029607-e09eb2dc-80c7-404b-99f1-03f4cebf54ae.jpeg" alt="happin" width="200" height="200"/>

## 📚 목차

- [개요](#개요)
- [과제 내용](#과제-내용)
- [팀 정보](#팀-정보)
- [담당 페이지 및 구현 기능](#담당-페이지-및-구현-기능)
- [실행 방법](#실행-방법)



## 개요

### Happin **프로젝트 Front-end소개**

- Pinterest **이미지 공유 SNS**를 참고하여 프로젝트를 진행했습니다.
- 첫번째 보다 더 적은 기간이 주어졌기에 최대한 **기간 내에 구현할 수 있는 기능들을 위주**로 진행했습니다.
- 개발은 초기 세팅부터 전부 직접 구현했으며, 시연영상에서 보이는 부분은 모두 백앤드와 연결하여 실제 사용할 수 있는 서비스 수준으로 개발한 것입니다.

### 🗓 수행 기간

> 2022.10. 04 - 2022.10. 13(2주)
</br>

### 🌼 Skill

: React.js, styled-components, RESTful API

### 🌼 협업툴

: Notion, Slack, Git(GitHub)

## ❗️과제 내용
#### Nav
- 검색기능 구현

#### 로그인, 회원가입
- 카카오 API로 진행

#### 관심사 페이지 
- 사용자가 회원가입 완료 후 관심사 필수 3개  선택하도록 기능 구현

#### 메인 페이지
- 무한스크롤 
- 다중 필터
- 핀 저장 기능 구현 

#### 상세 페이지
- 핀 이미지 및 정보 노출
- 작성자 프로필, 이름, 이메일 노출
- 핀 저장 기능 구현
- 이미지 링크 복사 기능 구현 
- 이미지 다운로드 기능 구현

#### 핀 생성 페이지
- api호출(유저 정보 가져오기)
- Formdata를 이용한 백엔드로의 이미지 업로드
- 이미지 파일 string data로 인코딩하여 미리보기 구현
- 관심사 선택하여 이미지에 대한 정보 추가
- 원하는 폴더에 생성한 이미지 저장 가능하도록 구현

#### 마이페이지 - 저장됨
- 다른 사람의 핀이 저장되는 곳
- 보드 추가 및 삭제 기능 구현
- 보드 대표 썸네일 노출 되도록 구현
- 보드 선택 시 보드에 담긴 핀들을 볼 수 있도록 기능 구현

#### 마이페이지 - 생성됨
- 내가 생성한 핀이 저장되는 곳
- 핀 저장 및 삭제 기능 구현


<br />



<br />

## 팀 정보

-  프론트엔드: 이유진, 안수진, 조재현 
- 백엔드: 조경찬, 김응수 


<br />

## 담당 페이지 및 구현 기능

![part2](https://user-images.githubusercontent.com/105909665/209518834-1a1c70c8-cbb1-449a-81aa-e844c030bb2e.gif)
![part3](https://user-images.githubusercontent.com/105909665/209518977-8e1eea1f-adb0-4acc-b284-fd733238663d.gif)

### 1. 이미지 생성 페이지
- 이미지 생성 페이지를 통해서 이미지의 정보와 관련 태그 설정 가능하게 구현
- 사용자의 정리 보드를 선택하여 이미지를 저장 가능
- 이미지를 업로드하면 생성 페이지에서 미리보기 가능하게 구현

### 2. 이미지 저장 보드 관리 페이지
- 저장할 보드를 생성/삭제 가능
- 보드를 클릭하여 접근한 후 저장된 이미지를 확인/삭제하는 기능 구현

## 실행 방법

해당 프로젝트를 로컬서버에서 실행하기 위해서는 Git 과 Npm (node.js를 포함) 이 설치되어 있어야 합니다.

1. 레파지토리 클론

   ```
   git clone https://github.com/bigwave-cho/37-2nd-happin-frontend.git
   ```

2. packages 설치

   ```
   npm install
   ```

3. 실행

   ```
   npm start
   ```

<br />

## **Reference**

- 이 프로젝트는 핀터레스트(https://www.pinterest.co.kr/)를 참고하여 제작하였습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
- 이 프로젝트에서 사용하고 있는 사진은 언스플래쉬(https://unsplash.com/) 소유이므로 무단 사용 시 문제가 될 수 있습니다.
