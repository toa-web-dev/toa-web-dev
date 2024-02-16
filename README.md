### Hi there 👋

# 포트폴리오
## 1. [Graphify_dev_note](https://github.com/toa-web-dev/Graphify_dev_note) 개인 프로젝트
  - 프로젝트 기간: 
  - 사용 스택: HTML SCSS Javascript React Next 
  - 배포: Vercel
## 2. [Photoswipe](https://github.com/toa-web-dev/Photoswipe) 개인 프로젝트
  
  - 프로젝트 기간: 
  - 사용 스택: HTML SCSS Javascript React Next 
  - 배포: Vercel
    
## 3. [Leisure-Link-Plus](https://github.com/toa-web-dev/Leisure-Link-Plus) 팀 프로젝트

 **레저링크_플러스**는 위의 레저링크 프로젝트를 개인적으로 코드 리뷰하고 개선한 `회고 프로젝트`입니다.
  - 프로젝트 기간: 23-09-26 ~ 23-10-03 (8일)
- 사용 스택: HTML CSS Javascript React Recoil
- 인원: 본인 1명
- 배포: firebase
프로젝트가 끝난 뒤에도 레저링크_플러스라는 이름으로 코드 리뷰를 진행해 재사용 되지 못하던 모달창 컴포넌트를 수정하고, 전역 상태 관리를 위해 사용된 라이브러리 Recoil의 atom이 Redux의 action처럼 잘못 사용되었던 점을 수정하며 회고를 진행했습니다.
- 배운 점: 여러 인원이 작성한 코드를 통합하면서 처음 정했던 코드 작성 시 규칙이 잘 지켜지지 않거나, 회의 때 미리 협의했지만 진행하면서 빠진 부분을 발견하고 수정 했습니다. 짧은 일정 속에 핫픽스를 진행하면서 느낀 점은, 팀과 함께 작업할 때는 합의된 규칙을 잘 지키고 개발 중인 내용의 변경 점은 없는지 소통하며 개발하는 것이 원활한 일정을 위해서 중요하다는 것을 배웠습니다.


<details>
  <summary><i>레저링크</i>는 부트캠프에서 진행한 팀 프로젝트로, 게시글을 작성하고, 다른 게시글을 추천하고 북마크 할 수 있는 여행지의 사진을 공유하는 사이트입니다.</summary>
  
  - 프로젝트 기간: 2023-08-24~2023-09-19 (27일) 
  - 사용 스택: HTML CSS Javascript React Recoil
  - 인원: 본인을 포함한 프론트엔드 4명 / 백엔드 3명
  - 배포: AWS
  - 역할: 
   프론트엔드 팀 내에서 각자 어떤 기능을 개발해야 하는지 회의를 이끌었습니다. 백엔드 팀과의 소통하며 백엔드 팀과 작업 현황을 공유하고 앞으로의 개발 목표를 회의했습니다.
   Github로 공유한 코드를 통합하는 작업을 수행하였습니다. 이전 프로젝트의 경험을 기반으로 본격적인 개발에 앞서 변수 이름 작명 규칙과 프로젝트에 사용되는 컴포넌트를 미리 설정하고 개발을 시작하자는 의견을 제시했습니다. Github에 개발 목표를 문서화해두어 각자 맡은 작업 영역과 구현해야 할 기능을 확인하는 데 유용했습니다. 
   내성적인 팀원이 버그로 종일 고민했다는 이야기를 듣고, 1시간 이상 해결되지 않는 문제는 공유하며 함께 해결하기로 제안하며 같이 오류를 해결하면서 팀과 함께 즐겁게 작업했습니다. 
   메인 페이지를 구현하였습니다. 메인 페이지에 사용자가 업로드한 사진을 서버에서 응답받아 화면에 배치해야 했는데, 바둑판처럼 균일하게 배치하면 자칫 정적이고 지루해 보인다고 생각해 인상 깊게 배치할 방법을 고민했습니다. 그 결과 무한 스크롤로 이미지를 불러오는 기능은 사진의 높이에 따라 자연스러운 차이가 생기게 배치하여 이미지가 단순하게 나열되지 않게 했습니다. 이는 Intersection Observer와 useRef로 스크롤의 바닥을 인식하면 fetch로 데이터를 요청해 display: grid로 구성된 각각의 세로 열에 이미지를 추가하는 방식으로 구현했습니다. 이렇게 구현한 무한 스크롤 모듈은 React 커스텀 hook으로 모듈화하여 재사용하기 쉽게 했습니다.
    AWS로 구현된 백엔드에서 API를 통해 통신하였으며, Postman으로 API를 문서로 만들어 관리하며 프론트엔드와 백엔드 팀이 협의하며 API를 개선해나갔습니다. 
</details>




<!--
**toa-web-dev/toa-web-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
