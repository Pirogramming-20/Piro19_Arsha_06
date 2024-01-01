# Piro20_Arsha_06

<!------------------------------------- part 1: 하종 ---------------------------------------->

## 1️⃣part1 ➜ 송하종

### 구현부분

- 상단 nav바, 첫번째 메인 화면, about us섹션

### 전체적인 특징

- 레이아웃을 flex, margin: auto등을 이용하여 화면비를 좀 더 중요시 함
- 아쉬운 점은 width가 매우 좁아졌을 때의 레이아웃까지는 신경 못씀

### 각 섹션 별 특징

1. 상단 nav바

- hover시 색 변화, dropdown list 애니메이션의 구현
- position : sticky를 통한 상단 고정

2. 첫번째 메인 화면

- get start, watch video hover시 색 변화, img의 up-down 애니메이션
- 로고 hover시 확대와 색변화

3. about us섹션

- learn more 버튼의 hover시 색변화

<br>

<!------------------------------------- part 2: 재영 ---------------------------------------->

## 2️⃣part2 ➜ 원재영

### 구현 부분

- "ABOUT US"의 두 번째 화면 (이하 "why us 화면")
- "ABOUT US"의 세 번째 화면 (이하 "skills" 화면면)
- "SERVICES" 화면
  <br>

### 각 섹션 별 특징

1. <b>"why us" 화면</b>

- 화면을 left-section과 right-section으로 나누어 left-section에는 글자가, right-section에는 그림이 오도록 배치
- left-section의 question 부분은 checkbox 속성을 이용하여 클릭될 때마다 속성이 check가 되도록 하여 밑에 텍스트 부분이 나타나도록 함.
- 또한, radio 속성을 이용하여 사용자가 한 번에 하나의 question-answer만 볼 수 있도록 함
- 페이지를 새로고침할 때마다 페이지에 있는 요소들이 작은 크기에서 시작했다가 원래 크기로 커지는 애니메이션을 주었음

2. <b>"skills" 화면</b>

- 화면을 left-section과 right-section으로 나누어 left-section에는 그림이, right-section에는 글자가 오도록 배치
- 진행바가 채워지는 부분은 #e8edf5색 영역이 0.9초에 걸쳐 #37517e색 영역으로 바뀌는 애니메이션을 줌으로써 구현
- 페이지를 새로고침할 때마다 right-section에 있는 그림은 왼쪽 아래에서 원래 위치로 날아오고, left-section에 있는 그림은 오른쪽 아래에서 원래 위치로 날아오는 애니메이션을 주었음

3. <b>"services" 화면</b>

- 화면 상단의 제목과 글자 부분은 "services-title" 영역으로, 화면 하단의 box 부분은 "item-box" 영역으로 나눔
- 각 박스에 마우스를 호버하면 박스가 10px만큼 위로 올라감
- 박스의 "service-name" 부분에 마우스를 호버하면 텍스트의 색상이 바뀌고, 그 부분을 클릭할 수 있도록 마우스가 grab으로 바뀜
- 페이지를 새로고침할 때마다 "services-title" 영역의 텍스트들은 아래에서 원래 위치로 올라오고, "item-box" 영역의 박스들은 작게 시작했다가 원래 크기로 커지는 애니메이션을 주었음

### 아쉬웠던 점

- 해당 화면이 사용자의 viewport에 들어올 때 딱 한 번만 애니메이션을 주는 방법을 몰라 그냥 페이지가 새로고침될 때마다 애니메이션이 발생하도록 한 것

<br>

<!------------------------------------- part 3: 기택 ---------------------------------------->

## 2️⃣part3 -> 오기택

### 구현 부분

- "Call To Action"
- "PORTFOLIO"
- "TEAM"
- 세부분 호버 및 반응형까지 구현

### 각 섹션 별 특징

1. Call To Action

- 백그라운드 이미지를 화면에 고정시키고 앞쪽에는 linear-gradient을 통해 텍스트 그라데이션을 적용
- 백그라운드 이미지를 고정시켰기 때문에 스크롤을 내릴때 뒷 배경이 바뀌는 모습을 볼 수 있음
- Call To Action 버튼위에 마우스를 올릴시 호버 효과 구현
- 페이지 화면 크기에 따라 반응하도록 구현
- 스크롤에 따라 반응하도록 문구와 버튼에 애니메이션 효과 부여

2. PORTFOLIO

- 화면을 새로고침 하였을때 문구와 사진이 나타나도록 애니메이션 효과 부여
- All,App,Card,Web 버튼 호버시 색상 변경 및 클릭 시 해당 버튼에 맞는 이미지가 보이도록 설정
- 이미지 호버시 줌인효과 및 설명바 생성
- 페이지 화면 크기에 따라 반응하도록 구현

3. TEAM

- 화면을 새로고침 하였을때 문구와 사진이 나타나도록 애니메이션 효과 부여
- 각 박스에 호버시 조금씩 커지도록 트랜지션 설정
- 아이콘 호버시 색상이 변하도록 설정 / 아이콘 클릭시 아이콘에 해당하는 링크를 새창에 생성
- 페이지 화면 크기에 따라 반응하도록 구현

### 아쉬웠던 점

- 스크롤 기반으로 반응하며 페이지 새로고침 할때마다 한번씩만 애니메이션이 적용되도록 하는 방법을 많이 고민해봤으나 html과 css만으로 적용하는것을 하지 못해 아쉬움

<br>

<!------------------------------------- part 4: 채연 ---------------------------------------->

## 2️⃣part4 ➜ 박채연

### 구현 부분

- pricing ,frequently asked questions ,contact ,footer 총 4개의 section으로 구분함
- for_margin_padding으로 주어 통일되게 margin 과 padding값을 줌
- 반응형까지 구현 못함
- 아이콘은 font awesome 에서 불러옴
- 변수명이 겹치지 않게 하기 위해 뒤에 4를 붙임 (예외로 frequently asked questions에서만 id 명을 scales 11,22,33,44,55 로 둠)

### 각 섹션 별 특징

1. pricing
   -flex로 정렬, 적절한 아이콘 배치, hover

2. frequently asked question

- hover, input type="radio", transform:rotate 이용해서 클릭시 세부설명과 아이콘에 변화를 줌

3. contact

- 적절한 아이콘 배치, 지도api는 복붙함
- label, input으로 form 만듦

4. footer

- form,input 으로 email 입력창 만듦
- 아이콘, part 3의 코드 재사용+ skype svg만 추가하고 색상 변경
- Useful Links 클릭시 페이지 내 해당 위치로 이동하도록 설정
