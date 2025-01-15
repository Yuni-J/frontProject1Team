## 프론트 프로젝트_이젠병원 

### 개발 기간
2024.08.19 ~ 2024.08.26

### 팀 소개 
<div style="width: 100%;">
  <table style="width: 100%; border-collapse: collapse; text-align: center;">
    <thead>
      <tr style="text-align: center;">
        <th style="border: 1px solid #c6c6c6; padding: 8px; text-align: center;">이름</th>
        <th style="border: 1px solid #c6c6c6; padding: 8px; text-align: center;">역할</th>
        <th style="border: 1px solid #c6c6c6; padding: 8px; text-align: center;">기능</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">엄상훈</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">팀장</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">Header, Footer, Main contents 1번, 병원소개 상세페이지</td>
      </tr>
      <tr>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">박준희</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">팀원</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">회원가입, 로그인, 로그아웃, 정보수정, Main contents 2번</td>
      </tr>
      <tr>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">정슬빛</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">팀원</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">회원 예약 메인 / 상세 페이지, 비회원 예약</td>
      </tr>
      <tr>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">지윤희</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">팀원</td>
        <td style="border: 1px solid #c6c6c6; padding: 8px;">진료과 & 진료원 메인 / 상세 페이지, Main contents 3번</td>
      </tr>
    </tbody>
  </table>
</div>
<br><br>

## 📖 프로젝트 소개
한달 동안 배운 HTML, CSS, JS를 활용하여 화면 프로젝트를 진행하였습니다. 저희 팀은 프로젝트 주제로 '병원'으로 정하였고 '인하대병원'과 '아주대병원'을 참고하여 만들었습니다. 병원 프로그램에 맞는 다양한 기능을 구형하기 위해 팀원들이 각각 역할을 분담하여 작업을 진행하였습니다. <br>프로젝트는 병원 관련 다양한 서비스를 제공하는 것을 목표로, 진료 예약 시스템, 병원 소개, 진료과목 안내, 회원 관리 시스템 등을 포함한 웹사이트를 구현하였습니다. 
<br><br>

## 🛠 개발 환경 및 도구
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
<br><br>

## 🖥️ Main
<img width="948" alt="메인" src="https://github.com/user-attachments/assets/95e3ad3f-e867-456e-90d0-7efdc89b6f47" />
<br><br>

## ⭐ 기능 설명
### 회원가입, 로그인
- 회원가입이 승인되면 로컬 스토리지에 작성한 정보를 저장하여, 로그인 시 해당 정보가 일치하는지 확인합니다. 
- 사용자가 로그인할 때 입력한 정보는 로컬 스토리지에 저장된 정보와 비교되며, 일치할 경우 정상적으로 로그인 처리가 됩니다. 

<img width="948" alt="로그인(2)" src="https://github.com/user-attachments/assets/7a7b5b02-72c0-4a5d-bd9e-66bf3af4d095" />

### 진료과 & 읜료진
- 검색창에 진료과명을 입력하거나 초성 검색을 통해 사용자가 빠르게 원하는 정보를 찾아볼 수 있습니다. 
- 진료과에 대해 더 자세히 확인하고 싶을 때는 각 진료과 목록에 a 태그를 이용하여 해당 진료과의 상세페이지로 이동할 수 있게 만들었습니다. 

<img width="948" alt="의료과(2)" src="https://github.com/user-attachments/assets/47f5d855-24db-40ec-93e3-a2bf0a7b9b60" />
<img width="948" alt="의료과(3)" src="https://github.com/user-attachments/assets/13a0652c-aa78-4cd0-a563-dd84bcc205e2" />


### 예약하기
- 예약하기 탭을 별도로 만들어 사용자가 예약을 쉽게 진행할 수 있도록 했습니다. 예약은 단계별로 진행되며, 각 단계를 체크하면서 순차적으로 예약을 완료할 수 있습니다.

<img width="948" alt="예약하기" src="https://github.com/user-attachments/assets/70f0d254-d497-4d89-9cf7-7dfab4212a21" />


### 오시는길
- 탭 메뉴를 만들어서 각 지역별로 병원 위치 지도롸 오는 방법이 누른 항목에 맞게 바뀌도록 구현 하였습니다.
- 카카오 API를 이용해서 지도를 가져와 병원 위치에 마커와 이름을 표시하도록 구현하였습니다.

<img width="841" alt="오시는길" src="https://github.com/user-attachments/assets/455bdd29-62f1-4799-9fc6-c55964b722ca" />










