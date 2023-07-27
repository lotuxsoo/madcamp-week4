# What's Your Type
---

Week4 4분반 경민,수연팀

- 네가지의 유형테스트를 제공합니다.
- 소개팅유형 테스트, 개발자 유형테스트 , 연애 유형 테스트, 밈테스트
- 결과를 카카오톡 공유하기가 가능합니다.
- 결과를 보기 위해 광고를 띄움으로써 수익을 창출 할 수 있습니다.
- 테스트 결과에 맞는 유튜브 영상이나 결과이미지를 제공합니다.

---

### a. 개발 팀원

- 김경민 - 한양대학교 컴퓨터소프트웨어학부 19학번
- 최수연 - 숙명여자대학교 컴퓨터과학전공 19학번

---

### b. 개발환경

- Language: React.js, Django
- IDE: Visual Studio code

---

### c. Web applicaiton 소개

### 1.Main page

<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/055b5074-72d4-4af3-b75b-1cbc1f5082f0" width="1000" height="700">


***Major features***
- 애플리케이션의 제목인 "What's Your Type?"이 한 글자씩 나타나며 애니메이션 효과를 주는 기능이있습니다. 애니메이션은 무한히 반복됩니다.
- 사용자는 네 가지 다른 성향 테스트 중 원하는 것을 선택할 수 있습니다. 각 테스트 버튼을 누르면 해당 테스트 페이지로 이동합니다.

---

***기술설명***
- 사용자가 입력한 직군 정보를 통해 Designer와 Developer를 구분하여 서로 다른 form을 보여줍니다. 
- 입력을 완료한 경우 onsubmit을 호출해 서버로 data를 넘기고, 서버에서 mongodb에 insert하는 방식입니다.
- 사용자가 입력한 정보는 모두 useState를 통해 내용이 변화할때마다 실시간으로 업데이트 됩니다.

---

### 2.TestPage

<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/0362736c-ceb1-4e87-8a10-1888786e813d" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/5a9f2de4-1f07-443f-9854-43129ba361a6" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/e53c373d-b772-44d3-bba0-bde5dc4eb12a" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/274cfa55-6b5a-4f0f-ae9d-092a15bbb05f" width="1000" height="700">

***Major features***
- 원하는 경우 포트폴리오 내용을 수정할 수 있습니다.

---

***기술설명***
- 

---

### 3.ResultPage

<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/17b66718-85d4-4c69-ab2f-727a6d2ef6d9" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/c2657233-9a8b-4c8f-84f5-18f4cddd5e9e" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/f8777e2d-f267-42ea-85d5-3cb10f27a67b" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/8f5f479d-3afd-4985-930e-95c31cd571eb" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/251a13a6-9296-442b-8266-35fa8469f548" width="1000" height="700">
<img src="https://github.com/lotuxsoo/madcamp-week4/assets/55384167/26a21d48-d466-486a-8d47-0e67167255cb" width="1000" height="700">

***Major features***
- 사용자가 데이터베이스에 있는 모든 포트폴리오를 검색할 수 있습니다.
- 사용자이름, 직군과 일치하는지 확인하여 실시간으로 결과를 필터링할 수 있습니다.
- 검색 결과에서 포트폴리오 항목을 클릭하면 해당 포트폴리오에 대한 페이지로 이동합니다

---

***기술설명***
- 사용자 데이터를 비동기로 가져오는 기능은 React의 useEffect와 axios 라이브러리를 이용해 구현되었습니다. 
- 특정 시간이 지난 후에 HTTP 요청이 발생하고, 요청이 완료되면 사용자 데이터가 앱의 상태로 설정됩니다.
- 포트폴리오를 클릭하면 navigate를 통해 portfolio의 id에 해당하는 값의 viewcv로 전환됩니다.

---
