# usKet_TID ( 가제 : 티드 )

 👉  **Today I Define**

 👉  **1 day  / 1 tid 🏃🏻‍♂️**

### ✔️ 아이디어

- 세상을 바라보는 시각은 우리 모두가 다르기 때문에 단어를 보고 떠오르는 **의미, 이미지, 생각, 감정** 등 각양각색일 것이며 시간이 지남에 따라 변하기도 할 것이다.
- 자신만의 표현으로 단어를 정의해보고 단어에 대한 감정을 기록하고 가장 먼저 떠오르는 단어를 적어보면서 내가 바라보고 있는 세상은 어떤 세상인지, 또 단어에 대한 나의 정의나 의미가 어떻게 변화해 가는지 알아가보면 어떨까하는 생각에서 착안했다.

### ✔️ 기능

- 단어 - 사전에 저장한 단어들 중에서 랜덤하게 단어가 나온다. ( 기존의 정의된 단어는 배제 )
- 단어 선택 - 정해진 단어 혹은 다른 단어로 선택할 수 있다.
- 감정 + 처음 떠오르는 단어 + [정의 / 의미] + [이유 / 단어를 사용한 간단한 글] 순서로 입력하고 저장한다.
- 태그 - 각 단어에 자신이 생각하는 태그를 넣고 검색에 활용한다.
- 통계 - 타임라인(꾸준함), 감정의 분포, 태그 분포, 단어에 대한 정의, 감정의 변화 등을 보여 준다.
- (선택사항) 내가 바라보는 세상 - 인쇄물로 받을 수 있게 만들어보면 어떨까.
- (선택사항) 공유 - 다른 유저들의 정의를 함께 볼 수 있다.

### ✔️ 컬러 및 폰트 : 심플 is BEST 😂

- 흰색 : 백그라운드
- 검정색 : 글씨 및 버튼
- 폰트 : **카페24 고운밤** [ https://fonts.cafe24.com/ ]
- DarkMode 지원
### ✔️ 오픈소스 및 API

- Realm : 단어, 감정, 처음 떠오르는 단어, 정의 등을 저장한다.
- PNChart : 통계에 활용한다.
- 우리말샘API : 단어의 뜻을 가지고온다. ( 1일/ 50,000회, 그 이상은 불가능 하지만 Excel 파일로 가지고 올 수 있다. )

### ✔️**배포**
- iOS : 15.0 이상
- 유료 버전으로 배포해보고 싶다. 나에게는 50여명의 소비자가 확보되어 있다. ( By Jack )

### ✔️ UI & UX

<img src="https://user-images.githubusercontent.com/53691249/142445742-40080331-31ec-4ead-8e04-88babdbe90bd.jpg" width="80%" height="80%">


- 메인, 통계, 설정 : TabBar
- 메인 : TableView
- 우측 상단 버튼 : 단어 추천, 선택 → Editor Page ( 사진과 다름 )
- 통계 : PNChart를 이용 Card 형태의 UI 
<br></br>

👉 **Notion** : **[이터레이션 및 일정관리🧑🏻‍💻](https://jasper-atom-7c6.notion.site/a815c7d1282143f1bdcca2bd7eda7c16)**

### 🏃🏻‍♂️ 1일차, 2일차

- [x]  iOS Version
- [x]  Asset : Launch, AppIcon, logo, instagram
- [x]  Font : Cafe24Oneprettynight
- [x]  OpenSource : Realm / SideMenu
- [x]  MVC + Extension


### 🏃🏻‍♂️ 3일차

- [ ]  오늘의 단어 : ViewController, 새로운 단어 뽑기, 우리말샘 API로 뜻가져오기, 저장 버튼으로 값 전달
- [ ]  SearchBar OpenSource
- [ ]  CollectionView + CollectionViewCell
