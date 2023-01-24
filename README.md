

# 프로젝트 소개

### 언어치료실 홈페이지 제작  (프론트)

[개요] 언어치료실 '로뎀나무발달센터' 소개 사이트 제작   
[팀원] 윤명지 (개인프로젝트)   
[기간] 2020.06    

✔  사용 언어  : html, css      
✔  주요 기능 : 언어치료실인 '로뎀나무발달센터'의 소개   
✔  구현 과정 : html 및 css를 활용하였으며, a태그의 href를 활용하여 정적인 페이지 제작   
<br>
---------------------------------------
<br>
<br/>
<br/>
<주요 개발 내용>   
<br/>
전체적으로 header, aside, section, nav (+클래스가 im_bar인 사진)를 이용하여 화면을 배치하였습니다. (html마다 배치가 조금씩은 다르지만, 전체적으로 비슷합니다.)   
거의 대부분의 곳들에 링크를 걸어두어 어떤 페이지에서도 다른 페이지로 넘어갈 수 있도록 하였습니다.   

<br>
(1) index.html (메인 화면)      
header부분에 여러 span을 div로 묶어 메뉴를 만들어주었습니다. 메뉴에는 큰 주제들에 대한 html을 각각 링크 걸어주었습니다. 그 밑에는 이 사이트에서 사람들이 자주 들어갈 만한 곳들을 빠르게 들어갈 수 있도록 div를 사용해 링크 걸어두었습니다. 이는 각각에 클래스를 걸어두어 css 중 넓이와 높이, float:left;를 사용해 정렬하였습니다.   
<br/>
(2) intro.html (메뉴 중 센터소개)
메뉴 중 ‘센터소개’를 클릭하면 센터소개의 여러 세부 주제인 인사말, 둘러보기, 오시는 길 중 인사말(intro.html)이 연결됩니다. 이는 p를 사용하여 문단을 나누어 인사말을 작성하였
고, 각각을 class를 걸고 css를 사용하여 정렬이나 색상을 조절해주었습니다. 세부주제가 있는 부분들은 nav로 묶여져 있는 부분으로 각각을 클릭하면 그에 맞는 html이 나옵니다.
둘러보기를 클릭하면 센터의 전경을 볼 수 있는 picture.html이 연결되며, 오시는 길을 클릭하면 센터를 찾아오는 방법을 명시해둔 way.html이 연결됩니다. 이 두 html도 인사말인
intro.html과 마찬가지의 방법으로 p와 class를 사용해 만들었습니다.   
<br/>
(3) program.html (메뉴 중 ‘치료 프로그램’)   
메뉴 중 ‘치료 프로그램’을 클릭하면 program.html로 연결이 됩니다. 이는 센터에서 진행하는 프로그램들이 어떤 프로그램이 있고, 어떻게 치료하는지에 대해 설명된 부분입니다.왼쪽 부분에 세부주제들이 있고 이는 (2)와 같이 nav로 묶여져 있으며 클릭하면 각 링크로 연결이 됩니다. 각 링크는 언어치료(pro_language.html), 인지학습 치료(pro_cognitive.html),
미술치료(pro_art.html), 음악치료(pro_music.html)입니다. 이 4개의 세부주제들은 모두 p를 사용하였고 class를 걸어주어 css로 배치를 조절해주었습니다.   
<br/>
(4) advice.html (메뉴 중 ‘상담/예약’)   
메뉴 중 ‘상담/예약’을 클릭하면 advice.html로 연결이 됩니다. 이는 상담과정과 상담예약 부분이 있습니다. 위에 부분에 써져 있는 상담과정을 클릭하면 상담과정 부분으로 상담예약 부분을 클릭하면 상담예약 부분으로 내려가는 식으로 웹 페이지 내부 이동 기능(a태그에,id 속성 사용)을 사용하였습니다. 각 문단의 주제들은 h2를 사용하여 제목 효과를 주었고, 내용은 p를 사용하였으며 class를 주고 css를 이용하여 정렬해주었습니다.   
<br/>
(5) community.html (메뉴 중 ‘커뮤니티’)   
메뉴 중 ‘커뮤니티’를 클릭하면 community.html로 연결이 됩니다. 이는 ‘로그인 후 이용해주세요’ 라는 문구를 h2를 사용하여 작성하였고, 그 밑에 로그인 하기라는 것을 만들어 그 부분을 클릭하면 login.html로 연결되게 하였습니다.   
<br/>
(6) login.html (메뉴 중 ‘커뮤니티’에서 ‘로그인하기’)   
메뉴 중 ‘커뮤니티’를 클릭하고 ‘로그인하기’를 클릭하면 login.html로 연결됩니다. 이는 로그인을 하는 페이지로 type=“text”를 input하여 아이디와 비밀번호를 작성하는 박스를 만들어주었고, 아이디 저장과 자동로그인을 중복클릭 할 수 있도록 type=“checkbox”를 input 해 주었습니다. 마지막 로그인 버튼은 id를 걸어주어 css를 사용하여 둥글게 하는 등 으로 꾸며주었습니다.   

<img width="386" alt="image" src="https://user-images.githubusercontent.com/110431203/214211019-5f04e2ca-fb38-46f2-9b3f-f80332bd0181.png">

