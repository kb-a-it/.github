<div align="center">

<!-- 프로젝트 대표 이미지 -->
<!-- <img src="./assets/anchack-banner.svg" width="100%" alt="안착 프로젝트 배너"> -->

# 안착

### 낯선 지역으로 이주하는 사용자를 위한 맞춤형 동네 추천 서비스

목적지, 예산, 통근시간과 생활 선호도를 바탕으로  
사용자에게 적합한 동네를 추천하고 비교합니다.

<br>

<p align="center">
  <a href="https://github.com/kb-a-it/anchack-frontend"><img src="https://img.shields.io/badge/FRONTEND-REPOSITORY-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Frontend Repository"></a>&nbsp;&nbsp;
  <a href="https://github.com/kb-a-it/anchack-backend"><img src="https://img.shields.io/badge/BACKEND-REPOSITORY-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Backend Repository"></a>
</p>

</div>

---

## 프로젝트 소개

타지역이나 연고가 없는 지역으로 이주하는 사용자는  
지역의 특성과 주거환경에 대한 정보가 부족해 자신에게 맞는 동네를 선택하기 어렵습니다.

기존 부동산 서비스가 사용자가 이미 선택한 지역의 매물을 탐색하는 데 집중한다면,  
**안착은 매물을 찾기 전 “어느 동네에서 살아야 하는가”를 먼저 제안합니다.**

사용자가 입력한 목적지, 예산, 최대 통근시간, 선호 주거 유형과 생활 선호도를 바탕으로  
적합한 동네를 추천하고, 추천 이유와 지역별 정보를 함께 제공합니다.

---

## 주요 기능

<table width="100%">
  <thead>
    <tr>
      <th width="25%" align="center">맞춤 조건 입력</th>
      <th width="25%" align="center">동네 추천</th>
      <th width="25%" align="center">동네 비교</th>
      <th width="25%" align="center">지도·리뷰</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="25%" valign="top">
          목적지와 최대 통근시간<br>
          보증금·월세 예산<br>
          선호 주거 유형<br>
          생활요소별 중요도
      </td>
      <td width="25%" valign="top">
          필수 조건 필터링<br>
          행정동별 지표 분석<br>
          사용자 가중치 적용<br>
          추천 순위와 근거 제공
      </td>
      <td width="25%" valign="top">
        통근시간 비교<br>
        예산 적합성 비교<br>
        생활 인프라 비교<br>
        치안·환경 비교
      </td>
      <td width="25%" valign="top">
        추천 지역 지도 표시<br>
        주변 시설 조회<br>
        행정동 상세정보<br>
        거주 경험 리뷰
      </td>
    </tr>
  </tbody>
</table>

---

## 시스템 아키텍처

Frontend와 Backend를 분리하고, 외부 API와 공공데이터에서 수집한 정보를  
가공·저장하여 동네 추천과 지역 탐색 기능에 활용합니다.

<p align="center">
  <img
    src="./assets/architecture.svg"
    width="100%"
    alt="안착 시스템 아키텍처"
  >
</p>

---

## 기술 스택

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" alt="Vue.js">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000" alt="JavaScript">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <br>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Spring_Framework-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Framework">
  <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" alt="Gradle">
  <br>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion">
</p>

> 데이터베이스 및 세부 라이브러리는 각 Frontend·Backend Repository에서 확인할 수 있습니다.

---

## 프로젝트 산출물

<p align="center">
  <a href="기획안-링크"><b>프로젝트 기획안</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="사용자조사-링크"><b>사용자 조사</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="요구사항정의서-링크"><b>요구사항 정의서</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="기능명세서-링크"><b>기능 명세서</b></a>
  <br><br>
  <a href="화면설계서-링크"><b>화면 설계서</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="ERD-링크"><b>ERD</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="API명세서-링크"><b>API 명세서</b></a>
</p>

---

## Repository

<table width="100%">
  <tr>
    <th width="50%">Frontend</th>
    <th width="50%">Backend</th>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/kb-a-it/anchack-frontend">
        <img
          src="https://img.shields.io/badge/anchack--frontend-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"
          alt="anchack frontend"
        >
      </a>
      <br><br>
      사용자 조건 입력, 추천 결과,<br>
      동네 비교 및 지도 화면
    </td>
    <td align="center">
      <a href="https://github.com/kb-a-it/anchack-backend">
        <img
          src="https://img.shields.io/badge/anchack--backend-6DB33F?style=for-the-badge&logo=spring&logoColor=white"
          alt="anchack backend"
        >
      </a>
      <br><br>
      회원, 추천 로직, 지역 데이터,<br>
      리뷰 및 API 처리
    </td>
  </tr>
</table>

---

## 팀원 구성

<table width="100%">
  <thead>
    <tr>
      <th width="20%">현석원</th>
      <th width="20%">최보윤</th>
      <th width="20%">강제욱</th>
      <th width="20%">박민정</th>
      <th width="20%">석정한</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/swhyeon98">
          <img
            src="./assets/members/seokwon.png"
            width="190"
            alt="현석원 GitHub"
          >
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/B0Y00N">
          <img
            src="./assets/members/boyoon.png"
            width="145"
            alt="최보윤 GitHub"
          >
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/orinuguri26">
          <img
            src="./assets/members/jewook.png"
            width="190"
            alt="강제욱 GitHub"
          >
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/3iron">
          <img
            src="./assets/members/minjeong.png"
            width="180"
            alt="박민정 GitHub"
          >
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/JungHan-Seok">
          <img
            src="./assets/members/jeonghan.png"
            width="195"
            alt="석정한 GitHub"
          >
        </a>
      </td>
    </tr>
    <tr>
      <td align="center"><b>Team Leader</b></td>
      <td align="center"><b>Recommendation</b></td>
      <td align="center"><b>Region &amp; Map</b></td>
      <td align="center"><b>Member Management</b></td>
      <td align="center"><b>Route &amp; Mobility</b></td>
    </tr>
    <tr>
      <td align="center">
        추천 조건 입력·저장<br>
        추천 실행 연동<br>
        프로젝트 통합 관리
      </td>
      <td align="center">
        추천 계산<br>
        추천 결과·비교
      </td>
      <td align="center">
        지도 기반 동네 탐색<br>
        지역 데이터
      </td>
      <td align="center">
        회원·권한 관리<br>
        리뷰·신고 운영
      </td>
      <td align="center">
        주소·경로 API<br>
        통근 기능
      </td>
    </tr>
  </tbody>
</table>

---

## 협업 문서

<p align="center">
  <a href="https://github.com/kb-a-it/.github/blob/main/CONTRIBUTING.md">
    <b>개발 공통 규칙</b>
  </a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/kb-a-it/.github/blob/main/docs/TEAM_RULES.md">
    <b>팀 운영 규칙</b>
  </a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/kb-a-it/anchack-frontend/blob/main/docs/CODE_CONVENTION.md">
    <b>Frontend 코드 컨벤션</b>
  </a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/kb-a-it/anchack-backend/blob/main/docs/CODE_CONVENTION.md">
    <b>Backend 코드 컨벤션</b>
  </a>
</p>

---

<div align="center">

### Team A-IT

**KB IT's Your Life 7기 종합실무 프로젝트**

낯선 동네에서의 안전한 정착, 안착

</div>
