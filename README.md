# News Web


## Subject
React x Naver News 검색 API를 사용하여 News Web Page 구현

카테고리 버튼 클릭 시, 카테고리 분야에 맞는 News 리스트 출력

## MEMBER
* [김도현](https://github.com/thovy) 🌷
* [명지안](https://github.com/주소) 🌼
* [박미희](https://github.com/PMH2906) 🌻
* [이세운](https://github.com/sleet99) :rose:

## RESULT
UI화면구성

<img src="/UI.png" width="300" height="250">

Web 동작 gif


## Trouble Shooting
:exclamation: [Trouble Shooting](./TroubleShooting.md) :exclamation:

## 느낀점
강의 시간에는 React와 Node.js를 사용한 API연동을 따로 배웠지만, 해당 프로젝트에는 두 개의 연동이 필요해 난이도가 매우 어려웠다. React(Cient)와 API연동 Server의 연동을 위해 중간 서버(proxy server)를 거쳐 연동하였다. 또한 카테고리 버튼을 클릭 시 해당 분야에 맞는 뉴스를 재스크롤 가능하도록 구현하기 위해 fetch 함수를 사용하였고, /routes/index.js파일(API와 연동된 Server)에서 request의 query를 이용하여 값을 받을 수 있도록 구성하였다. 해당 프로젝트에서 client와 Server 사이의 데이터의 응답/요청에 대해 깊이 있게 배울 수 있었다. 

## REFERENCE
* Naver NEWS 

  [https://news.naver.com/](https://news.naver.com/)

* Node X React 연동

  [https://gaemi606.tistory.com/33 ](https://gaemi606.tistory.com/33)

  [https://singa-korean.tistory.com/46?category=829618](https://singa-korean.tistory.com/46?category=829618)

* Node X React 데이터 공유 

  [https://bloodstrawberry.tistory.com/365](https://bloodstrawberry.tistory.com/365)  

* Naver 검색 API 연동

  [https://developers.naver.com/docs/serviceapi/search/blog/blog.md#%EB%B8%94%EB%A1%9C%EA%B7%B8](https://developers.naver.com/docs/serviceapi/search/blog/blog.md#%EB%B8%94%EB%A1%9C%EA%B7%B8)                                                


## STACK
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/></a> 
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a> 
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a> 
<img src="https://img.shields.io/badge/react-61DAFB?style=flat-square&logo=react&logoColor=black"/></a>

