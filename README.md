### 2021 K-Digital Training 인공진능 융합서비스 개발자 과정
### 스마트인재개발원 bareuda 
# BERT 기반 화장품 리뷰 분석 서비스 (팀명: 바르다)
<img width="1224" alt="스크린샷 2022-09-27 오후 4 12 43" src="https://user-images.githubusercontent.com/99772968/192460193-bb7fb55c-d1c1-48e8-832a-f0a4fcca8242.png">

## 서비스 소개
* 서비스명 :  BERT 기반 화장품 리뷰 분석 서비스 
* 서비스설명 : 
  *  여러 화장품을 비교하여 시간을 단축시킬 수 있고, 리뷰 분석을 통해 합리적인 제품 결정 유도
  *  간단한 문진을 통해 본인의 피부 타입을 확인하고 본인 피부에 맞는 화장품을 추천
  *  팬데믹 이후 가속화된 온택트(온라인 + 언택트) 시대 나의 피부 타입에 맞는 제품 추천을 받을
    수 있음
<br>
## 날짜: 프로젝트 기간
2022.04.22 ~ 2022.06.03 (6주)
<br>
## 프로젝트 특장점
 * BERT모델 긍정 부정 리뷰 분석을 통해 제품의 특징을 보여줌.
 * 바우만 테스트를 통한 피부 진단 후 타입에 맞는 화장품 추천
 * 화장품 리뷰 분석을 통해 화장품의 특징을 한눈에 볼 수 있도록 제작하여 화장품에 대한 정보를      효과적으로 제공
<br>
##프로젝트 개발 내용
* 바우만 테스트를 통한 피부타입 진단
* 제품 추천
  * 피부 타입과 일치하는 제품 추천
* 리뷰 분석
   * 리뷰 긍정율/부정율
   * 구매자 피부 타입 분포
   * 긍정 리뷰 워드클라우드 부정 리뷰 워드클라우드
   * 긍정키워드 부정키워드 빈도수
* 검색을 통해 두가지 화장품을 비교  
* 회원가입, 좋아요 서비스 구현
<br>
## 서비스 내용
<img width="1512" alt="스크린샷 2022-09-27 오후 5 38 33" src="https://user-images.githubusercontent.com/99772968/192668278-7a6ee488-beda-400c-ab31-e8021b32adf5.png">

<img width="1512" alt="스크린샷 2022-09-27 오후 5 38 42" src="https://user-images.githubusercontent.com/99772968/192668316-787b53f2-2469-4cdd-91d1-24637689f45f.png">

<img width="1512" alt="스크린샷 2022-09-27 오후 5 38 49" src="https://user-images.githubusercontent.com/99772968/192668345-67f56fb9-ad4f-43d4-bb23-1cadc72916f5.png">

<img width="1512" alt="스크린샷 2022-09-27 오후 5 38 56" src="https://user-images.githubusercontent.com/99772968/192668375-70bcb8f0-ffaf-493b-b894-01153aedcd62.png">

<img width="1512" alt="스크린샷 2022-09-27 오후 5 39 04" src="https://user-images.githubusercontent.com/99772968/192668414-b05d5d46-b142-4ca3-ac39-2cf8f9bfab83.png">

<img width="1512" alt="스크린샷 2022-09-27 오후 5 39 11" src="https://user-images.githubusercontent.com/99772968/192668452-ecf22455-5aaf-4619-a39f-7b9f9c2d00ab.png">

<img width="1512" alt="스크린샷 2022-09-27 오후 5 39 18" src="https://user-images.githubusercontent.com/99772968/192668520-9b6d6d2f-d062-41cd-85df-32310ebcdf5d.png">

<img width="1512" alt="스크린샷 2022-09-27 오후 5 39 21" src="https://user-images.githubusercontent.com/99772968/192668559-130f3ff4-e21d-4ce9-9c57-a514fab685ef.png">


## 기술스택
<table>
    <tr>
        <th>구분</th>
        <th>내용</th>
    </tr>
    <tr>
        <td>사용언어</td>
        <td>
            <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white"/>
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"/>
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>라이브러리</td>
        <td>
            <img src="https://img.shields.io/badge/BootStrap-7952B3?style=for-the-badge&logo=BootStrap&logoColor=white"/>
            <img src="https://img.shields.io/badge/KakaoMap-FFCD00?style=for-the-badge&logo=Kakao&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>개발도구</td>
        <td>
            <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=Eclipse&logoColor=white"/>
            <img src="https://img.shields.io/badge/RaskpberryPi-A22846?style=for-the-badge&logo=RaskpberryPi&logoColor=white"/>
            <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white"/>
            <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>서버환경</td>
        <td>
            <img src="https://img.shields.io/badge/Apache Tomcat-D22128?style=for-the-badge&logo=Apache Tomcat&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>데이터베이스</td>
        <td>
            <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=Firebase&logoColor=white"/>
            <img src="https://img.shields.io/badge/Oracle 11g-F80000?style=for-the-badge&logo=Oracle&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>협업도구</td>
        <td>
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/>
        </td>
    </tr>
</table>
<br>
## SW유스케이스
<img width="1404" alt="스크린샷 2022-09-27 오후 5 23 57" src="https://user-images.githubusercontent.com/99772968/192474046-dbcb3265-33dd-4983-b24a-7f539a02ffe0.png">

<br>
## 서비스 흐름도
<img width="1240" alt="스크린샷 2022-09-27 오후 5 08 40" src="https://user-images.githubusercontent.com/99772968/192471055-abfc9142-57cc-46ed-8f56-cb844c9f2420.png">

<br>
## ER다이어그램
<img width="844" alt="스크린샷 2022-09-27 오후 5 22 06" src="https://user-images.githubusercontent.com/99772968/192473656-37fd043f-e7cf-44bc-a582-fd1ace734e0a.png">

<br>
## 화면 구성
### 로그인/회원가입/회원괸리/회원수정/회원탈퇴
![image](https://user-images.githubusercontent.com/25995055/178401098-95f15a0e-a2de-415e-83d5-883bb4cb0656.png)
<br>
## 팀원 역할
<table>
  <tr>
    <td align="center"><img src="https://item.kakaocdn.net/do/fd49574de6581aa2a91d82ff6adb6c0115b3f4e3c2033bfd702a321ec6eda72c" width="100" height="100"/></td>
    <td align="center"><img src="https://mb.ntdtv.kr/assets/uploads/2019/01/Screen-Shot-2019-01-08-at-4.31.55-PM-e1546932545978.png" width="100" height="100"/></td>
    <td align="center"><img src="https://mblogthumb-phinf.pstatic.net/20160127_177/krazymouse_1453865104404DjQIi_PNG/%C4%AB%C4%AB%BF%C0%C7%C1%B7%BB%C1%EE_%B6%F3%C0%CC%BE%F0.png?type=w2" width="100" height="100"/></td>
    <td align="center"><img src="https://i.pinimg.com/236x/ed/bb/53/edbb53d4f6dd710431c1140551404af9.jpg" width="100" height="100"/></td>
    <td align="center"><img src="https://pbs.twimg.com/media/B-n6uPYUUAAZSUx.png" width="100" height="100"/></td>
  </tr>
  <tr>
    <td align="center"><strong>함정재</strong></td>
    <td align="center"><strong>이도연</strong></td>
    <td align="center"><strong>박소연</strong></td>
    <td align="center"><strong>김재혁</strong></td>
    <td align="center"><strong>이윤호</strong></td>
  </tr>
  <tr>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>Frontend</b></td>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>Frontend</b></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/자신의username작성해주세요" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/자신의username작성해주세요" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/자신의username작성해주세요" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/자신의username작성해주세요" target='_blank'>github</a></td>
    <td align="center"><a href="https://github.com/자신의username작성해주세요" target='_blank'>github</a></td>
  </tr>
</table>
## 트러블슈팅
* 문제점<br>
 BERT 모델 학습과정에서 학습 데이터의 편향의로 인해 잘못된 결과가 나옴
* 해결방안<br> 
 6000개 이상의 데이터를 직접 라벨링(정확도 82%, 재현율 80%, 정밀도 80%까지 올림)


Shift + Return 키를 눌러 새 행을 추가합니다
