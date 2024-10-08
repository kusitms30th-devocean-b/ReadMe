## 👫 팀명

🤍 B(팀 최고 데보)숑

> **기업 데보션과 B팀 모두 최고가 되겠다는 포부를 담은 귀여운 팀명입니다.**

<br>

## 🏃‍♂️ R&R 분배

| **분야** | **이름** | **포지션** |
| --- | --- | --- |
| 기획 | 전희수 | 📈 PM, 서비스 기획 - 서비스 정책 확립, 와이어프레임 작성, UX writing, 기획안 작성 |
| 기획 | 김규리 | 📊서비스 기획 - 서비스 정책 확립, 와이어프레임 작성, UX writing, 기획안 작성 |
| 기획 | 김서연 | 📋 서비스 기획 - 서비스 정책 확립, 와이어프레임 작성, UX writing, 기획안 작성 |
| 디자인 | 진성이 | 🔐 디자인 리드,  UI/UX 디자인, GUI디자인, 배지 디자인 |
| 개발(FE) | 류주아 | 🔦 프론트엔드 리드, 나의 배지, 나의 서랍, 마일리지 팝업 UI 및 API 연동 |
| 개발(FE) | 안연아 | 📱 나의 작성 글, 나의 관심 글 페이지, 나의 랭킹 대시보드, 전체 랭킹 페이지 UI 및 API 연동 |
| 개발(BE) | 한상호 | 💻 백엔드 리드, DB 및 나의 서랍, 나의 배지 분석 API 구축 |
| 개발(BE) | 한성민 | 🖥️ DB 및 랭킹, 나의 배지 목록 API 구축 |

<br>

## 💻 데스크 리서치_자사 분석

데보션의 개인화 정보를 강화하며, 회원 간의 활동 정보를 서로 공유함으로써 선의의 경쟁을 유발하고, 게이미피케이션 요소를 활용해 [컨텐츠 작성의 동기 유발을 목적으로 하는 데보션 마이페이지 UX/UI 개선]을 위해 데보션의 SW 분석을 실시하였습니다.

<br>

### (1) **데보션의 Strength**

- 현직 개발자들이 공유하는 다양한 최신 개발, IT Industry 정보들이 블로그를 통해 매일 업데이트 된다.
- 다양한 사람들의 작업물에 대해서 커뮤니티 내 다양한 소통이 가능하다.
- 활발한 커뮤니티 활동을 통해 마일리지를 모을 수 있고, 획득한 마일리지를 실제 제품으로 교환할 수 있다는 차별점을 가지고 있다.

<br>

### (2) **데보션의 Weakness**

1. **활동 내역 조회 화면 속, 직관적으로 내용을 인지하기 어려운 UX Writing과 파편화된 메뉴 구성**
    - 활동 내역 조회 하위 메뉴에서 정확히 어떤 정보가 등장할 지 파악할 수 없다.
        - 가령 ‘커뮤니티’ 칸을 클릭했을 때 사용자가 ‘작성한’ 커뮤니티 글을 확인할 수 있는 것인지, 사용자가 ‘열람한’ 커뮤니티 글을 확인할 수 있는 것인지 파악할 수 없어 개선이 필요하다.
            

             ✅ 기존 홈페이지 내 사용자 활동 내역 조회 메뉴 클릭 시
            
            ![image](https://github.com/user-attachments/assets/8a633382-9219-43c7-8972-c6eedd394bdc)

          
            - 커뮤니티: 사용자가 작성한 커뮤니티 글 내역 확인 가능
            - 댓글: 다른 사용자의 커뮤니티 글에 작성한 댓글 내역 확인 가능
            - 좋아요: 다른 사용자의 커뮤니티 글에 좋아요 한 내역 확인 가능
            - 북마크: 다른 사용자의 커뮤니티 글에 북마크 한 내역 확인 가능

            <br>
   
    
    - 좋아요 한 커뮤니티 글은 마이페이지에서 확인 가능하나, 북마크 한 커뮤니티 글은 커뮤니티 메뉴 페이지에서만 확인 할 수 있다. ‘좋아요’와 ‘북마크’ 모두 커뮤니티 글을 열람하고 따로 보관해두는 과정에서 발생하는 사용자 행동임에도 불구하고, 조회할 수 있는 경로가 다르다는 점에서 혼란이 야기된다.
    - TECH 글에 좋아요를 누르거나 댓글을 작성한 활동 내역은 마이페이지를 비롯한 홈페이지 어디에서도 확인 할 수 없다. TECH 글은 SK 현직자가 작성한 글로, 사용자에게 유의미한 정보로 사료되나 이를 따로 모아볼 수 없다는 점에서 개선이 필요하다.
        
        ✅ 데보션 사용자의 활동 내역 확인 경로
        
        | **활동 내역** | **확인 경로** |
        | --- | --- |
        | 좋아요 한 커뮤니티 글 | 마이페이지 |
        | 북마크 한 커뮤니티 글 | 커뮤니티 |
        | 좋아요 한 tech 글 | 확인 불가 |
        | 커뮤니티에 작성한 글 | 마이페이지 |
        | 커뮤니티 글에 작성한 댓글 | 마이페이지 |
        | TECH글에 작성한 댓글 | 확인 불가 |
        <br>

2. **데보션 서비스의 다양한 기능을 경험해보고, 꾸준히 사용하도록 하는 동기부여 장치의 부족**
    - 배지 시스템이 마련되어 있으나, 배지 디자인의 미공개 등 배지 획득의 효능을 직접적으로 느끼지 못해 데보션을 꾸준히 이용하도록 하는 동기부여로는 부족함이 존재한다.
    - 현재 출석 배지, 공감 배지, 댓글 배지만 존재해 데보션의 모든 서비스를 이용하기 어렵다. 배지의 종류가 단순하고 낮은 레벨만으로 구성되어 있어 데보션 서비스를 폭넓게 이용할 수 없다.
    - 배지를 획득 시 몇 마일리지가 적립되는지 사용자가 알 수 없다.
<br>

3. **사용자의 활동 현황을 가시적으로 보며 선의의 경쟁을 할 수 있는 공간의 부재**
    - 현재 데보션 인사이드에서는 구현이 되어 있는 랭킹 시스템이 데보션에는 도입이 되어 있지 않다.
        
        ![image](https://github.com/user-attachments/assets/794df18d-2097-4713-b689-aa7be2551fd4)

        > 데보션 인사이드의 ‘랭킹’ 모습
        
    - 사용자들의 활동 현황을 가시적으로 보여주어 선의의 경쟁을 할 수 있는 공간과 기능이 존재하지 않다.
    - 사용자에게 성취와 보상을 제공하여, 데보션 서비스 이용률과 몰입도를 높일 수 있는 로직이 부족하다.

<br>

## 👀 경쟁사 분석

|  | 데보션 | 커리어리 | OKKY | velog | stackoverflow |
| --- | --- | --- | --- | --- | --- |
| 프로필 정보 설정 및 공개 | o | o | o | ▵<br> - 경력 o<br> - 관심분야 x | ▵<br> - 경력 x<br> - 관심분야 o |
| 커뮤니티 유무 | o | o | o | o | x |
| 커뮤니티 종류 | 4 | 1 | 3 | 1 | x |
| Q&A 가능 여부 | o | o | o | x | o |
| 자체 콘텐츠 제작 및 제공 | o | x | x | x | x |
| 동기부여를 위한 게이미피케이션 | 배지 | x | 랭킹 | x | 배지, 랭킹 (평판) |
| 보상 체계 | o | x | x | x | x |
| 특징 | - 개발 지식 공유 및 소통 중심<br>- SK 내외부 개발자 간 접촉 가능<br>- SK 현직자가 제공하는 자체 컨텐츠 열람 가능 | - 장문의 게시글 작성 중심<br>- 현직자 Q&A 가 존재하나, 현직자 아닌 일반 사용자도 답할 수 있어 메리트 부재 | - 단문의 게시글 작성 중심<br>- 지식 커뮤니티 / 일상 커뮤니티의 구분<br>- 구인구직, 국비지원캠프 등 정보 제공 | - 개인 포트폴리오 관리 용도에 중심<br>- 글 작성 과정의 고도화 | - 에러 질문에 대한 답변 중심<br>- 직관적인 UX/UI 설계 |

<br>

### ❗ 데보션 만의 차별성

  **1️⃣ 데보션 내에서의 적극적인 소통이 가능하다.**

- 최신 개발 지식들이 매일 공유되고, 현직 개발자들에게 작성한 글에 대한 피드백을 받을 수 있다.

  2️⃣ **활동 성취감을 고취시키는 보상체계가 존재한다.**

- 데보션 활동을 통해 얻은 마일리지를 상품으로 교환할 수 있다.

<br>

## 📊 유저 리서치_사용성 테스트와 IDI(In Depth Interview)

현 데보션 마이페이지에서 **사용자들이 느끼는 데보션의 강점과 약점**은 무엇인지 파악하고자 유저 리서치를 실시하였습니다.

<br>

### (1) 사용성 테스트

- 앞선 데스크 리서치에서 얻은 문제인식을 기반으로 ‘개발에 대한 필요한 지식을 관련 커뮤니티에서 얻고자 하며, 개발자로 활동하거나 개발자 취업을 준비하고 있는 사람’을 인터뷰이로 설정했습니다. 총 6명의 사용자들에게 **‘현재 데보션 커뮤니티에 대한 사용성 테스트’**를 진행했습니다.
    
    ![image](https://github.com/user-attachments/assets/ccbc333c-0977-4c09-8b87-abada5f9487d)

    
- 사용성 테스트의 경우 [컨텐츠 작성의 동기 유발을 목적으로 하는 데보션 마이페이지 UX/UI 개선]이라는 과제에 맞게 데보션의 **마이페이지의 주요 기능을 카테고리화**하여 task 를 구성했습니다. 이를 통해 사용자가 기능을 사용하는데 있어 어떤 부분에서 불편함과 만족감을 느끼는지 확인하고자 했습니다.
    
    ### 📌 사용성 테스트 내용
    
    - **마일리지**
        - 얼마만큼의 마일리지를 보유하고 있는지 파악하실 수 있나요?
        - 해당 마일리지를 어떻게 획득할 수 있는지 파악하실 수 있나요?
        - 마일리지를 어떻게, 무엇을 위해 사용할 수 있는지 파악하실 수 있나요?
    - **작성 글 / 열람 글 조회**
        - 작성한 글의 목록을 찾으실 수 있나요?
        - 댓글 남긴 글이 어떤 내용인지 파악하실 수 있나요?
        - 내가 북마크한 글 중 [특정 키워드]의 내용이 담긴 글을 찾으실 수 있나요?
    - **배지**
        - 어떤 배지를 보유하고 있는지 파악하실 수 있나요?
        - 배지를 어떻게 획득할 수 있는지 파악하실 수 있나요?
        - 대표 배지를 바꾸실 수 있나요?
    
<br>

### (2) IDI(In Depth Interview)

- 사용성 테스트를 진행한 후 IDI 를 실시하여, 주어진 Task를 수행하는 과정에서 느낀 어려운 점과 인상깊은 점에 대해 자세히 들어보았습니다.
- 인터뷰 질문은 앞선 사용성 테스트 내용을 기반으로 마이페이지 기능에 만족 혹은 불만족한 부분에 대한 이유, 커뮤니티 이용에 대한 행태 및 그에 따른 PainPoint를 도출할 수 있는 문항들로 구성하였습니다.
    
    > * IDI의 전체적인 질문과 답변 내용은 별첨에서 확인할 수 있습니다.
    

> **마이페이지에서의 사용자 경험 인사이트**
> 

![image](https://github.com/user-attachments/assets/627c5bdb-bed6-4db4-b6bb-f008a591f117)


> **배지 기능에서의 사용자 경험 인사이트**
> 

![image](https://github.com/user-attachments/assets/909daae3-25b8-4bf4-b16e-5b66c41c82e1)

> **전반적인 커뮤니티 이용에 대한 사용자 경험 인사이트**
> 

![image](https://github.com/user-attachments/assets/2e3e9a69-1525-4048-8430-1f7bbf98a1f3)

사용성 테스트와 IDI 진행의 결과, 공통적으로 커뮤니티 이용 중 다음과 같은 3가지에 대해 **불만족**을 느끼고 있었습니다.

- 원하는 정보를 쉽게 찾을 수 없는 불편한 UI/UX
- 버튼인지 인식하기 어려운 UI
- 사용자 친화적이지 못한 UX Writing

또한, 불만족 지점 이외에도 기존 서비스에 대한 **사용자 만족 지점**을 발견할 수 있었습니다.

- 사용자 활동 수치 정보가 잘 나타나있는 UX
- 북마크 글 내에서의 검색 및 필터링 기능

<br>

### (3) 유저 리서치 인사이트

- 유저 리서치를 통해 발굴한 **불만족 지점**과 **만족 지점을** 기반으로 개선 방향 인사이트를 도출하였습니다.
    
    ![image](https://github.com/user-attachments/assets/1517c7b1-543d-4137-b752-8c0758188251)

    
    ![image](https://github.com/user-attachments/assets/71a78fcc-833d-44ac-9b59-facb1a7bf85b)

    
    ![image](https://github.com/user-attachments/assets/92cb0110-7f1a-430c-b2aa-54c2bd82295f)


이에 따라 기존 데보션 커뮤니티가 가지고 있는 **강점을 살리면서도 단점을 해소할 수 있는 서비스 개선안**을 제안하고자 합니다.

<br>

## 📑 문제 정의

데스크 리서치와 유저 리서치를 통해 **현 데보션의 마이페이지 구성이 커뮤니티 이용 동기를 부여하지 못한다는 문제를 발견하였습니다.** 구체적인 문제 발생의 원인은 다음과 같습니다.

<br>

### (1) 문제 발생의 원인

1. **나의 활동 현황을 한 눈에 파악할 수 없다.**
    - 현재 마이페이지에서는 커뮤니티 방문 횟수, 게시글 열람 및 작성 횟수 등 정량적인 활동 수치를 직관적으로 확인할 수 없다.
2. **나의 활동 내역을 쉽고 빠르게 찾아볼 수 없다.**
    - 현재 마이페이지에서는 모호한 워딩의 사용, 파편화된 메뉴 구성으로 게시글 열람 및 작성 내역의 조회 과정이 복잡하다.
    - 너무 많은 버튼이 나열되고, 카드형과 목록형이 혼재된 UI 화면으로 구성되어 정보 피로도가 증가한다.
    - 클릭이 가능한 메뉴인지 직관적으로 인지할 수 없다.
3. **마일리지, 배지 등 게시글 열람 및 작성 활동 보상에 대해 이해하기 어렵다.**
    - 현재 마이페이지에서는 마일리지 및 배지 획득 방법, 획득 후 활용할 수 있는 방법에 대한 설명이 부족하다.
    - 커뮤니티 우수 활동에 대한 직접적인 혜택을 체감하기 어렵다.
4. **재미 요소가 부재하다.**
    - 사용자가 자신의 활동을 다른 사용자와 비교하는 등의 게이미피케이션 요소가 부재해 데보션 서비스 몰입도가 낮다.
5. **새로운 사용자 유입의 부족하다.**
    - 데보션 홈페이지에 접속해 회원가입 및 로그인을 해야만 게시글의 내용을 확인할 수 있어, 데보션 커뮤니티의 접근성이 낮다.
    
    ### ✨ 문제 상황 정의
    
    1. 마이페이지 내 나의 활동 현황 및 내역 관리가 어려운 점
    2. 커뮤니티 활동 보상 내용의 이해도가 낮은 점
    3. 재미요소가 부재한 점
    
    위와 같은 점들을 때문에 **커뮤니티 소통을 위한 활동 동기를 높이지 못하고 있다**고 진단하였습니다. 더불어 데보션 커뮤니티에 **접근할 수 있는 장벽을 높은 상황**이라는 점도 문제 상황이라고 보았습니다.

이를 바탕으로 작성한 문제 가설은 다음과 같습니다.

<br>

### (2) 문제 가설

> ❗마이페이지 개선을 통해 커뮤니티 활동 동기를 높일 수 있을 것이다.

- 활동 현황을 가시적으로 보여주는 대시보드를 통해 사용자는 성취감을 느낄 수 있을 것이다.
- 작성한 글과 열람한 글을 조회할 수 있는 메뉴 구성의 UX/UI 개선을 통해 사용자는 자신의 활동 내역을 효율적으로 관리할 수 있을 것이다.
- 마일리지 및 배지에 관한 구체적인 정보 제시를 통해 사용자는 활동 보상을 명확하게 이해할 수 있을 것이다.
- 게이미피케이션 기능 추가를 통해 사용자의 커뮤니티 이용 몰입도가 높아질 것이다.
- 커뮤니티 작성글의 접근성 개선을 통해 새로운 사용자는 쉽고 빠르게 데보션을 접할 수 있을 것이다.

<br>

## 🧑‍💻 페르소나 및 고객여정지도

<br>

### (1) 페르소나

데보션 사용자의 특성에 따라 다음과 같은 두 가지 유형의 페르소나를 구성하였습니다.

| 메인 타겟 | 데보션을 이용중인 현직 개발자 |
| --- | --- |
| 서브 타겟 (잠재 고객) | 데보션을 처음 접하는 학생 개발자 |

> 데보션 커뮤니티 사용자의 80%가 데보션 인사이드 사용자라는 데보션 자체 데이터를 기반으로 메인타겟 선정

> 최신 개발 이슈를 현직자의 피드백과 함께 접할 수 있다는 데보션의 강점이 대학생 개발자에게 매력적으로 다가올 것이라는 유저 리서치 기반으로 서브 타겟 선정

- 메인 타겟 페르소나
    
   ![image](https://github.com/user-attachments/assets/7de0f6a8-2643-4949-aba2-85ec299fce7e)

    
- 서브 타겟 페르소나
    
   ![image](https://github.com/user-attachments/assets/c51138e3-d4dc-4a2d-bb87-1cbb6c3a819d)


도출된 2가지의 유형을 ‘데보션’을 사용할 가상의 사용자, 페르소나로 설정하여 그들의 Needs와 Pain Point를 발굴해보았습니다.

<br>

### (2) 고객 여정 지도

- 메인 타겟 고객 여정 지도
    
    ![image](https://github.com/user-attachments/assets/34ad8aec-afcd-4021-a2f9-31b5f3d34c22)

    
- 서브 타겟 사용자 여정 지도
    
    ![image](https://github.com/user-attachments/assets/8649f243-2512-4272-b2a9-4b500ce4629a)

    
각 페르소나의 데보션 이용과정에 대한 여정지도를 각각 그려봄으로써 사용자의 Pain Point를 발견하고, 인사이트를 도출하였습니다.

<br>

## 💡 솔루션

앞서 언급된 문제를 해결하기 위한 솔루션은 다음과 같습니다.

<br>

### **1. 활동 현황을 분석한 대시보드 추가**

- 사용자의 랭킹 정보와 배지 정보를 대시보드로 구성해 활동 현황을 직관적으로 인지하게 한다.
- 랭킹 대시보드에서 등수와 획득 마일리지, 출석 수, 댓글 및 글 작성 수와 같은 월간 활동 수치를 누적 막대 그래프로 시각화 한다.
- 배지 대시보드에서는 배지 획득 상황, 배지 획득 필요 요소 및 배지 획득 시 얻게 될 마일리지와 같은 월간 배지 정보를 시각화 한다.
- 지난 2개월의 랭킹 그래프도 함께 명시해 사용자의 활동 성장 추이를 확인할 수 있다.

<br>

### **2. 활동 내역 조회 메뉴의 UX/UI 개선**

- **나의 서랍 기능을 도입합니다.**
    - 기존 활동 내역 조회 메뉴를 나의 서랍으로 구성한다. 나의 작성 글’에서는 내가 작성한 글의 목록을 ‘나의 관심 글’에서는 좋아요, 댓글, 북마크한 글을 확인할 수 있다.

- **활동 내역 상세보기 화면을 개선합니다.**
    - TECH 코너의 글도 북마크 할 수 있게 메뉴를 추가한다. 또, 댓글, 좋아요, 북마크한 TECH 글을 조회할 수 있도록 개선해 사용자의 모든 활동 내역을 효율적으로 관리할 수 있다.
    - 활동 조회 상세보기 화면 내 카테고리 및 활동 종류 (북마크, 좋아요, 댓글) 설정 방식을 드롭박스로 변경한다.
    - 화면 사이즈가 작은 앱의 경우 활동 종류, 카테고리 등 선택 사안을 한 번에 모아서 선택할 수 있도록 필터 버튼과 바텀시트를 도입한다. 깔끔한 UI 개선을 통해 서비스 피로도를 완화할 수 있다.
    - 활동 내역 조회 상세보기 화면의 게시글 형태를 갤러리형으로 통일해, 직관적이고 간결한 화면을 경험할 수 있다.
    
    ![image](https://github.com/user-attachments/assets/2510efd8-cfbb-4246-853c-be617eae7d82)
    
    ![image](https://github.com/user-attachments/assets/28cd0e30-b046-440d-a2c3-10105ec3445c)

    ![image](https://github.com/user-attachments/assets/276c31d0-16f4-4fe9-bf2d-a401de9155f6)


<br>

### **3. 마일리지 내역 조회 UI/UX 개선**

- 마일리지 정책을 1 Depth 의 화면에서 바로 확인할 수 있도록 하고, 획득 마일리지 사용 방법에 관한 UX 라이팅을 추가한다.
- 7일 내 소멸 마일리지 정보를 안내하여 적극적으로 마일리지를 활용하도록 한다.
- 출석, 댓글, 나의 글 작성 시 1일 1회 마일리지를 지급하는 방식으로 기존 출석 시에만 기본 마일리지를 지급하던 마일리지 체계를 개선한다. 이를 통해 지속적인 커뮤니티 접속과 활동을 장려한다.
    
    ![image](https://github.com/user-attachments/assets/ac94f75a-9cfe-4ff6-a8a3-100686ff9d06)

<br>

### **4. 배지 시스템** UI/UX**개선**

- 방문 → 열람 → 댓글 → 게시글 작성의 서비스 활용 흐름에 따라 배지 종류를 구성하여, 전반적인 서비스 이해도를 향상한다. 댓글 배지와 작성 배지를 추가해 콘텐츠 작성 동기가 상승한다.
- 또한, 배지 획득 시 얻을 수 있는 마일리지 정보를 추가하여 사용자의 활동 동기를 강화시킨다.
- 나의 배지 목록 화면에서도 대표 배지를 설정할 수 있도록 변경해 배지 관리의 효율성을 높인다.
    
    ![image](https://github.com/user-attachments/assets/5ea40c26-3ed7-4589-bd82-0c3961604229)


<br>

### **5. 랭킹 기능 추가**

- ‘총 마일리지’ 를 반영한 월간, 연간 전체 랭킹 순위 구축한다. 이를 통해 경쟁 심리를 자극하고, 서비스 이용 재미요소를 더한다.
- 또한, 랭킹 순위 보상시스템을 도입해, 우수 활동자들에게 혜택을 부여하고 지속적인 활동을 장려한다.
- 랭킹 집계 방식에 대해 안내하는 팝업을 추가해 랭킹 기능에 대한 이해도를 높인다.

<br>

### **6. 도전-성취-보상의 순환시스템 구축**

- 사용자가 실질적인 혜택을 체감할 수 있는 마일리지 기능을 서비스 전반에 도입하여 커뮤니티 이용에 대한 효용성을 극대화 한다.
- 출석 뿐 아니라 댓글 작성과 게시글 작성의 활동을 마일리지 집계에 포함한다. 또한, 배지 획득 시 마일리지를 획득할 수 있도록 해 배지와 랭킹 시스템, 마일리지 간의 연결고리를 강화한다.

<br>

## 📐 IA 정보 구조도

![IA](https://github.com/user-attachments/assets/92ad9140-0b01-4f42-89cb-ba525836bd03)

<br>

## 🎨 GUI

<br>

### (1) 데보션 웹 GUI

> **마이페이지 > 나의 서랍**
> ![g1](https://github.com/user-attachments/assets/64a7506a-53be-428c-8102-2a869f7817b0)

> 마이페이지 > 나의 서랍 > **나의 작성 글**
> ![g2](https://github.com/user-attachments/assets/29deeef7-fc72-4ba8-a71b-0b60c712c569)

> 마이페이지 > 나의 서랍 > **나의 관심 글**
> ![g3](https://github.com/user-attachments/assets/650e82de-c93a-45ea-b499-efca4fd6bc91)
> ![g4](https://github.com/user-attachments/assets/8feb90b5-77af-4512-831e-e15ff0a4b982)

> 마이페이지 > 나의 활동 > **나의 랭킹**
> ![g5](https://github.com/user-attachments/assets/a8a1cc2e-447e-4ed3-970c-85c06a458f9f)

>  마이페이지 > 나의 활동 > 나의 랭킹 > **월간 랭킹**
> ![g6](https://github.com/user-attachments/assets/c23f5d33-9d13-4500-8eee-8bdeafe5b160)

> 마이페이지 > 나의 활동 > 나의 랭킹 > **연간 랭킹**
> ![g7](https://github.com/user-attachments/assets/043301c7-bd5e-4734-8a89-aa977e4c9d25)

>  마이페이지 > 나의 활동 > 나의 랭킹 > **전체 랭킹 보상**
> ![g8](https://github.com/user-attachments/assets/655796e0-2f34-42a9-b220-606ec6f8e9be)

> 마이페이지 > 나의 활동 > **나의 배지**
> ![g9](https://github.com/user-attachments/assets/fbd9052a-0fe4-4b3b-9d69-615bf0e6840f)

> 마이페이지 > 나의 활동 > 나의 배지 > **기본 배지**
> ![g10](https://github.com/user-attachments/assets/50968dda-d266-4bc2-bbb2-61839ab05f3f)

> 마이페이지 > 나의 활동 > 나의 배지 > **이벤트 배지**
> ![g11](https://github.com/user-attachments/assets/6c333a74-ae13-4c95-bede-25ab8b4818a9)

> 마이페이지 > 나의 활동 > 나의 배지 > **대표 배지**
> ![g12](https://github.com/user-attachments/assets/e85e383d-5f04-4160-b927-64ea35241fad)

> 마이페이지 > 나의 활동 > 나의 배지 > **배지 리디자인**
> ![g13](https://github.com/user-attachments/assets/8637d672-7fa0-42dc-a826-5c429f23d70b)

> **마이페이지 > 마일리지** 
> ![g14](https://github.com/user-attachments/assets/eea74419-a86a-4471-87a5-f39e31432714)

<br>

### (2) 데보션 앱 GUI

추가적으로, 반응형 웹임을 고려해 앱과 태블릿 GUI 디자인을 진행하였습니다.

> **마이페이지**
> ![g15](https://github.com/user-attachments/assets/b43f45ff-565c-4f61-830b-8765c6dcdcbf)

> 마이페이지 > 나의 서랍 > **나의 작성 글**
> ![g16](https://github.com/user-attachments/assets/8d0fe00e-9f91-4fd4-8bcf-96fcbcc2d07f)

> 마이페이지 > 나의 서랍 > **나의 관심 글 > 커뮤니티**
> ![g17](https://github.com/user-attachments/assets/e53ff8a9-33f6-4a88-bc1d-a6adca1f93fa)

> 마이페이지 > 나의 서랍 > **나의 관심 글 > TECH**
> ![g18](https://github.com/user-attachments/assets/2f10cff0-1917-4a1a-b192-c2ec1548a148)

> 마이페이지 > 나의 활동 > **나의 배지 > 나의 배지 목록**
> ![g19](https://github.com/user-attachments/assets/12403f69-220c-4ef3-b1c4-5675aff43412)
> ![g20](https://github.com/user-attachments/assets/c77d3e75-2ff9-4424-9f8a-7496324a7774)

> 마이페이지 > 나의 활동 > **나의 랭킹 > 전체 랭킹**
> ![g21](https://github.com/user-attachments/assets/d877a0e1-6c1d-42be-bb26-c76bd54ee1dd)

<br>

### (3) 데보션 테블릿 GUI

> **마이페이지**
> ![g22](https://github.com/user-attachments/assets/3f82c8d6-8e70-45a7-8428-0828f84bf9fa)

> 마이페이지 > 나의 서랍 > **나의 작성 글**
> ![g23](https://github.com/user-attachments/assets/cb4b0627-945b-432d-8603-7d956ce17103)

> 마이페이지 > 나의 서랍 > **나의 관심 글 > 커뮤니티**
> ![g24](https://github.com/user-attachments/assets/a395b1c8-c970-4dc8-af94-c5abc210150d)

> 마이페이지 > 나의 서랍 > **나의 관심 글 > TECH**
> ![g25](https://github.com/user-attachments/assets/1ce79c72-fd32-4fbe-a037-e4eb064007eb)

> 마이페이지 > 나의 활동 > **나의 배지 > 나의 배지 목록**
> ![g26](https://github.com/user-attachments/assets/7e967a4e-306d-458f-ab6f-c170bc362104)
> ![g27](https://github.com/user-attachments/assets/f18c38ce-3840-46f9-baef-7cd6888b9253)

> 마이페이지 > 나의 활동 > **나의 랭킹 > 전체 랭킹**
> ![g28](https://github.com/user-attachments/assets/5e31b068-c0ab-414c-b3f1-1ce42a267770)

<br>

## 💡추가 제안 솔루션

<br>

### 1. 데보션 커뮤니티 내 챌린지 진행 후 배지 지급

- 자발적인 게시글 작성 이외에도, 다양한 주제로 글을 작성하는 경험을 통해 커뮤니티 내에서 성취를 경험할 수 있도록 합니다.
    
    ### 📎 챌린지 내용 제시
    
    - SWD (‘이달의 주제 글 읽기 챌린지’ 배지 <Studying With DEVOCEAN>)
        1. 진행 방식
            - 1딘계 : 커뮤니티 및 블로그에 작성된 글의 키워드 언급량 분석을 통해 키워드를 결정
            - 2단계 : AI를 통해 해당 키워드를 이용한 질문 생성
        2. 예시 :
            - 1단계 : 언급량 키워드 1위 **“인공지능”**
            - 2단계 : AI 생성 질문 → “최근 전세계에서 인공지능을 통해 지구온난화를 극복하려는 시도가 일어나고 있습니다. 해당 시도에 대한 아이디어나 개인적인 의견이 있으신가요?“
            - 3단계 : 질문 및 키워드 관련 가이드 자료 제시
                - 데보션 TE : https://devocean.sk.com/search/techBoardDetail.do?ID=166712
                - 데보션 커뮤니티 : https://skdevocean.page.link/VNtW9WGxx1ztKrKq7
    - KWD (‘이달의 주제 글 쓰기 챌린지’ 배지 <Keep Writing With DEVOCEAN>)
        1. 진행 방식 
            - 1단계 : 커뮤니티 및 블로그에 작성된 글 제목의 사용된 키워드 언급량 분석을 통해 키워드를 결정 (월간 인기 키워드)
            - 2단계 : 글 작성 후 해당 키워드 해시테그를 달 경우 챌린지 참여 인정
        2. 예시 :
            - 1단계 : 월간 인기 키워드 제시 → ‘#코드리뷰 #지식그래프 #오픈랩’
            - 2단계 : 제시 키워드들 중 하나를 선택하여 글을 작성하고, 해당 키워드 해시테그를 달 경우 챌린지 참여 인정
            - 3단계 : 키워드 관련 가이드 자료 제시
                - 데보션 TECH : https://devocean.sk.com/search/techBoardDetail.do?ID=165226
                - 데보션 커뮤니티 : https://skdevocean.page.link/EPWZQNxp1wwSMiJs7

<br>

### 2. **내가 쓴 글 공유하기 기능 추가**

- ‘나의 작성 글’ 메뉴를 로그인 없이도 열람할 수 있도록, 웹에 게시할 수 있는 설정 버튼을 추가합니다.
- 이를 통해 데보션에 게시안 나의 작성 글을 다른 사람에게 공유할 수 있으며, URL 복사하기를 통해 개인 포트폴리오로도 활용할 수 있습니다.
    
    ![공유](https://github.com/user-attachments/assets/ed9e23d0-9c56-4a82-9489-8bff2eaaaeef)


<br>

## 🛠️ 사용스택

<br>

### 👥 공통

**`Maven`**

- 프로젝트 빌드와 의존성 관리를 위해 Maven을 사용하였습니다.
- 기존 프로젝트에서도 Maven을 사용하고 있어 기존 설정을 유지하는 것이 유리하며, 복잡한 의존성 관리가 상대적으로 간단해집니다.
- 또한, 표준화된 빌드 프로세스를 통해 유지보수와 협업 효율성을 높일 수 있기에 선택하였습니다.

<br>

### 📘 Frontend

**`JSP`**

- 기존 시스템의 안정성을 유지하고, Java 기반 기술과의 호환성을 고려하여 JSP를 사용하였습니다.
- JSP는 서버 사이드에서 HTML을 생성하고 Java 코드와의 통합이 용이하여, 복잡한 로직을 안정적으로 처리할 수 있기 때문에 선택하였습니다.

**`jQuery`**

- 클라이언트 사이드에서의 간편한 DOM 조작과 이벤트 처리를 위해 jQuery를 사용하였습니다.
- jQuery는 다양한 브라우저 간의 호환성을 보장하며, 간결한 문법을 통해 개발 생산성을 높일 수 있어 선택하였습니다.

<br>

### 📗 Backend

**`Java 8`**

- 기존 시스템이 Java 8을 기반으로 개발되어 있어, 호환성 유지를 위해 사용하기로 결정했습니다.
- Java 8은 람다 표현식, 스트림 API 등 유용한 기능을 제공하면서도 안정적이고 널리 사용되고 있는 버전입니다.
- 해당 버전을 유지함으로써 기존 코드의 재사용성을 높이고 예상치 못한 호환성 문제를 최소화 하고자 선택하였습니다.

**`MySQL 5.7`**

- 기존 시스템과의 호환성을 유지하기 위해 MySQL 5.7을 사용하였습니다.
- 5.7 버전은 2015년부터 출시되어 2023년 6월까지 주기적으로 업데이트되며, 성능과 안정성, 확장성 측면에서 충분히 검증된 버전입니다.
- MySQL 8.0으로의 업그레이드 시 5.7과의 변경점이 많아 호환성 문제가 발생할 수 있기 때문에, 안정성과 호환성을 고려하여 MySQL 5.7을 선택하였습니다.

**`MyBatis`**

- 기존 시스템과의 호환성을 유지하기 위해 MyBatis를 사용하였습니다.
- MyBatis는 데이터베이스와의 상호작용을 효율적으로 관리할 수 있는 프레임워크로, SQL 매핑 기능을 통해 복잡한 비즈니스 로직을 효율적으로 구현할 수 있기에 MyBatis를 선택하였습니다.

<br>

## 🖥️ ERD

<img width="1618" alt="erd" src="https://github.com/user-attachments/assets/9aee2260-62ef-4ddd-a71c-cf30e3fe7173">

<br>
<br>

## 🔗 아키텍쳐

<img width="753" alt="아키텍처" src="https://github.com/user-attachments/assets/819c7d90-e9a1-4ed0-8934-2ecd134b2488">

<br>
<br>

## 💭 개발 중 고려한 지점

<br>

### 👥 공통

1. Pull Request & Issue 템플릿을 구성하였습니다.
2. PR시 Reviewer 1명의 Approve를 받아야 Merge할 수 있는 룰을 팀 자체적으로 설정하였습니다. 코드 리뷰를 진행했으며, 이를 통해 코드 퀄리티를 개선할 수 있었습니다.
3. Git Flow 전략을 사용했습니다. 하나의 레포지토리에서 작업을 했기에, back 또는 front를 브랜치명에 붙여 구분하였습니다. (ex. `back/feature/#이슈 번호/작업 내용`)

<br>

### 📘 Frontend

1. 기존 코드 스타일 준수하려고 노력하였습니다.
    1. 동일한 기능의 경우 수정된 UI에도 기존 API를 연동할 수 있도록 하였습니다.
    2. API 연동 방식을 유지하기 위해 AJAX를 사용하였습니다.
    3. ‘나의 배지 목록’ 페이지를 구현하기 위해 앱에만 있던 ‘나의 활동 배지’ 코드를 가져온 후 추가적인 코드 작업을 하였습니다.
2. 사용자의 활동을 직관적으로 보여주기 위해 `Chart.js`를 사용하였습니다.
    1. 내가 쓴 글, 내가 쓴 댓글, 출석 수, 랭킹의 변화 데이터를 시각화 하였습니다. 
3. 나의 활동, 전체 랭킹과 관련한 새로운 페이지를 구축하였습니다.
    1. 기존 페이지와 동일한 CSS는 공통으로 사용하였습니다.
    2. 서버 쪽에서 리다이렉트를 처리하여 새로운 페이지에 접근할 수 있도록 설정하였습니다. 

<br>

### 📗 Backend

1. 기존 코드 스타일을 준수하려고 노력하였습니다.
    1. 기존에 사용하던 `Model` , `ModelAndView` 등 MVC 프레임워크를 사용하였습니다.
    2. 기존에 사용하던 메서드는 수정을 자제하고 분기 처리를 통해 메서드를 사용하는 이외 지점에서 사이드 이펙트가 발생하지 않도록 노력하였습니다.
    3. 신기능 구현 또는 수정 시 주석을 통해 기록을 남기고자 하였습니다.
2. 배지 획득 시, `badgeAction` 메서드를 이용하여 기존과 동일하게 1) 배지 획득 2) 배지 마일리지 적립 3) 알림 발송이 되도록 구현하였습니다.
3. `유저 활동 → 마일리지 획득 → 랭킹 상승`의 흐름으로 사용자의 참여도를 높이려고 노력하였습니다.
    1. 마일리지 정책에서 마일리지 제한 정책을 정의하여 랭킹에 도입하였습니다.
    2. `연간`, `월간` 랭킹 배지로 얻은 포인트는 제외하여, 사용자 간 초기 랭킹의 격차를 줄이고자 하였습니다.
4. `Optional.ofNullable()`를 통해 NPE를 방지하고자 노력하였습니다.
    1. SQL에서 객체로 매핑하는 과정에서 `NULL` 이 반환되고 이를 사용할 때 NPE가 API 에러의 주된 원인임을 알았습니다.
    2. `Optional.ofNullable().orElse()`를 이용하여 NPE로 인한 API 에러를 해결하였습니다.
5. 연간, 월간 랭킹 배지를 주기적으로 지급하는 과정에서 `Scheduler`를 사용하였습니다.
    1. 연간 랭킹 배지는 `매년 1월 1일 0시`에 지급합니다.
    2. 월간 랭킹 배지는 `매월 1일 0시`에 지급합니다.

<br>

## 📝 별첨

<br>

### UT 인터뷰 전체 내용

1. 인터뷰이 A
    
    ![별첨1](https://github.com/user-attachments/assets/2445c78a-56c1-4a72-970e-a7db3fc248c1)

    
2. 인터뷰이 B
    ![별첨2](https://github.com/user-attachments/assets/77d77c53-8bb0-4e12-8cbb-b6c1c88f742d)

    
3. 인터뷰이 C
    
    ![별첨3](https://github.com/user-attachments/assets/37ea201f-4f93-46f4-89cf-424b35b6a8d2)

    
4. 인터뷰이 D
    
    ![별첨4](https://github.com/user-attachments/assets/0c367b7f-ffb3-47d7-b885-fb3a1b2c0210)

    
5. 인터뷰이 E
    
    ![별첨5](https://github.com/user-attachments/assets/a7d2f37b-a4fa-4d74-b432-1d0a3606ae44)

    
6. 인터뷰이 F
    
    ![별첨6](https://github.com/user-attachments/assets/8616b95a-cf41-4a27-80cc-cac7cae1f31c)
