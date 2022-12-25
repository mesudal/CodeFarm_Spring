# CodeFarm의 '너와 농부싶어' 프로젝트

<div>
  <h2>청년농이란?</h2>
  <p><strong>청년농</strong>이란 도시 혹은 수도권에서 생활을 하던 청년들이 지방쪽 혹은 귀농에 적합한 장소로 이동을 하여 농사를 지으며 경제생활을 하는 것을 의미한다.</p>
  <p>너와 농부싶어 홈페이지는 청년농을 위한 다양한 정보 제공과 함께 소통공간 마련을 중심으로 기획한 프로젝트이다.</p>
</div>
<hr>


<div>
  <h2>프로젝트의 목적</h2>
  <p>매년 증가하는 귀농귀촌 인구들 중 20~30대 비중이 상당히 크다.<br>
    정부에서는 귀농인들을 위한 다양한 사업과 프로그램들을 운영하고 있지만, 늘어가는 청년농들에게 이러한 정보를 제공해주는 사이트는 별로 없다.<br>
    이러한 점을 극복하고자 귀농을 하기 전 다양한 정책들을 미리 확인하고, 자신이 귀농을 했을 때 잘 적응을 할 수 있게끔 그리고 노하우 등을 전수받을 수 있게끔 커뮤니티를 만들어 활성화를 시키면 정말 좋을     것 같다는 생각이 들어 이번 프로젝트를 기획하게 되었다.
  </p>
</div>
<hr>

<div>
  <h2>프로젝트에서 맡은 역할</h2>
  <p>퍼블리싱 : 메인페이지, 아르바이트</p>
  <p>백엔드 : 웹소켓을 활용한 실시간 채팅 기능 구현, 채팅 알림 구현, OAuth(구글) 구현</p>
</div>
<hr>

<div>
  <h2>프로젝트를 통해 느낀점(퍼블리싱)</h2>
  <p>우선 퍼블리싱부터 느낀 점은 메인 페이지 coment 페이지를 벤치마킹하여 작업을 진행하였는데 슬라이드 배너가 상당히 많이 필요했다.<br>
    많은 라이브러리 중 swiper slide 라이브러리를 활용하여 이번 프로젝트 분위기에 맞게끔 슬라이드 배너를 제작하였는데, 중간중간 나의 목적과는 다르게 작동하는 배너가 많이 미웠다.<br>
    하지만, 구글링과 조금씩 코드를 수정하며 원하던 기능 구현을 완성하였고, 메인 페이지 작업은 헤더를 포함하여 약 1주일 정도 작업을 진행한 것 같다.<br>
    또한, 아르바이트 페이지의 경우 게시글 작성 페이지와 상세 페이지에서 아르바이트 장소가 필요하여 지도 API를 사용해야 했다.<br>
    이번 프로젝트에서 처음으로 KAKAO 지도 API를 사용하였고, 생각보다 사용방법이 쉬워서 백작업에서 조금 쉽게 작업을 할 수 있게끔 최대한 기능을 미리 구현을 해놓은 것 같다.<br>
    퍼블리싱은 백엔드 업무와는 다른 방식으로 코드를 작성해야 했고, 프로젝트의 분위기를 생각하며 작업을 진행하다보니 부족했던 나의 퍼블리싱 능력을 이번 프로젝트를 통해 많이 성장시킨 것 같다.
  </p>
</div>

<div>
  <h2>프로젝트를 통해 느낀점(백엔드)</h2>
  <p>이번 프로젝트에서 백엔드 업무를 진행하며 정말 큰 어려움이 있었다.<br>
    한 번도 들어보지 못한 웹소켓이란 통신방법을 구현하여 이번 프로젝트에 적용을 시켜야 했고, 샘플링 코드가 있긴 했지만 모두 처음 보는 문법과 제대로 된 진행방향도 몰랐기에 큰 어려움이 있었다.<br>
    정말 많은 시간 동안 구글링을 하면서 약 1달 동안 고민을 하고, 코드를 수정하며 공부를 하였고 결과적으로는 sockJs와 stomp를 활용하여 실시간 통신을 완성하였다.<br>
    처음에는 막막하기만 했던 웹소켓을 한 번 구현에 성공을 하고나니 감이 잡히기 시작했고, 정말 크게 성장했음을 느꼈다.<br>
    구글 OAuth의 경우도 처음으로 도전하는 OAuth였지만, 구글에서 비교적 많은 정보를 제공해주었기에 그래도 짧은 시간 내에 완성을 한 것 같다.<br>
    이번 프로젝트에서 정말 벽도 크게 느끼고, 나의 개발능력에 대해서 크게 좌절하였지만 주변 팀원들의 응원으로 계속 도전할 수 있었고 성공적인 결과물을 만들 수 있어서 너무 뿌듯했다.
  </p>
</div>
<hr>

<div>
  <h2>프로젝트에 사용된 기술 스택</h2>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white" />
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jQuery&logoColor=white" />
  <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat&logo=Thymeleaf&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat&logo=Oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=Gradle&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=flat&logo=Socket.io&logoColor=white" />
</div>




